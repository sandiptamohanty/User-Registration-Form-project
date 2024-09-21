# User-Registration-Form-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> User Registration Form</title>
</head>
<body>
    <form action="get" target="_blank" action="/signup">
    <fieldset>
        <legend><b> User Registration!! </b></legend>
        <label for="Username">Enter Username:</lable> <input type="text" name="Username" id="Username" value="">
        <br>
        <br>

        <label for="Useremail">Enter Useremail: </label>
        <input type="email" name="Useremail" id="Useremail" placeholder="a@example.com" autofocus>
        <br>
        <br>
        
        <label for="UserPassword">Enter UserPassword:</label>
        <input type="Password" name="UserPassword" id="UserPassword">
        <br>
        <br>

        Gender 
        <label for="Male">Male</label>
        <input type="radio" name="Gender" id="Male" value="Male">
        <br>
        <br>


        <label for="Female">Female</label>
        <input type="radio" name="Gender" id="Female" value="Female">
        <br>
        <br>

        <label for="Transgender">Transgender</label>
        <input type="radio" name="Gender" id="Transgender" Value="Transgender">
        <br>
        <br>

        <input type="number" min="0">
        <br>
        <br>

        <input type="submit" value="submit form">
        </fieldset>
    </form>
