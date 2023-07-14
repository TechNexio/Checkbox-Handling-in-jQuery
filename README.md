# Checkbox-Handling-in-jQuery

<!DOCTYPE html>
<html>
<head>
    <title>Your Title</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body>

<input type="checkbox" id="myCheckbox"> Check me
<p id="message"></p>

<script>
$(document).ready(function() {
    $('#myCheckbox').change(function() {
        if(this.checked) {
            $('#message').text("Checkbox is checked.");
        } else {
            $('#message').text("Checkbox is not checked.");
        }
    });
});
</script>

</body>
</html>
