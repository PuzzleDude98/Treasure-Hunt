<html>
<head>
    <title>Enter Code</title>
</head>
<body>
<script type="text/javascript">
    function checkPswd() {
        var codeOne = "JSA9ND";
        var password = document.getElementById("pswd").value;
        var codeTwo = "ITSV9Q";
        var password = document.getElementById("pswd").value;
        if (password == codeOne) {
             window.location="JSA9ND";
        }
        elif (password == codeTwo) {
             window.location="ITSV9Q";
        }
        else{
            alert("Passwords do not match.");
        }
    }
</script>
<form>
    <label for="pswd">Enter your code: </label>
    <input type="password" id="pswd">
    <input type="button" value="Submit" onclick="checkPswd();" />
</form>
</body>
</html>
