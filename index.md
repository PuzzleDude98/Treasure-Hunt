<html>
<head>
    <title>Enter Code</title>
</head>
<body>
<form>
    <label for="pswd">Enter your code: </label>
    <input type="password" id="pswd">
    <input type="button" value="Submit" onclick="checkPswd();" />
</form>
<!--Function to check password the already set password is admin-->
<script type="text/javascript">
    function checkPswd() {
        var codeOne = "JSA9ND";
        var password = document.getElementById("pswd").value;
        if (password == codeOne) {
             window.location="clue2";
        }
        var codeTwo = "ITSV9Q";
        var password = document.getElementById("pswd").value;
        if (password == codeTwo) {
             window.location="clue3";
        }
        else{
            alert("Passwords do not match.");
        }
    }
</script>
</body>
</html>
