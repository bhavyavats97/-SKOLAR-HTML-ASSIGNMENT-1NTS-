<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form </title>
</head>
<body>
    <form action="/submit-form" method="post">
        <label for="uname">User Name: </label><br>
        <input type="text" id="uname" name="uname" placeholder="Enter your user name"><br>
        <label for="email">Email: </label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email"><br>
        <label for="password">Password: </label><br>
        <input type="password" id="password" name="password" placeholder="Enter your password"><br>
        <label for="terms">I agree to the terms and conditions: </label><br>
        <input type="checkbox" id="terms" name="terms" placeholder=""><br>
        <input type="submit" value="Submit">
    </form>

    
</body>
</html>
