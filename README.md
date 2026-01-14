<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Formate</title>
</head>

<body>
    <h1 style="width: 600px; margin: auto;">Form Tag</h1> <br> <br>

    <form style=" width: 600px; margin: auto;"> 
        <fieldset>

            <legend>Personal Info</legend> <br>

            <label for="Fname">First Name: </label> <br>
            <input required placeholder="First-Name" type="text" name="first_name" id="Fname"> <br> <br>

            <label for="Lname">Last Name: </label> <br>
            <input required placeholder="Last-Name" type="text" name="Last_name" id="Lname"> <br> <br>

            <label for="pass">Password: </label> <br>
            <input required placeholder="Password" type="password" name="password" id="pass"> <br> <br>

            <label for="email">Email: </label> <br>
            <input required placeholder="Email" type="email" name="email" id="email"> <br> <br>

            <label for="dateOfBirth">Date of Birth: </label> <br>
            <input required type="date" name="dateOfBirth" id="dateOfBirth"> <br> <br>

            <label for="fileName">Upload your File: </label> <br>
            <input type="file" name="file" id="fileName"> <br> <br>

            <p>Gender:</p>
            <input type="radio" name="gender" id="male">
            <label for="male">Male</label> <br>
            <input type="radio" name="gender" id="female">
            <label for="female">Female</label> <br> <br>

            <p>Choose Your Favorite Color :</p>
            <input type="checkbox" name="colors" id="white" checked> <label for="white">White</label>
            <input type="checkbox" name="colors" id="blue"> <label for="blue">Blue</label>
            <input type="checkbox" name="colors" id="red"> <label for="red">Red</label>
            <input type="checkbox" name="colors" id="green"> <label for="green">Green</label>
            <input type="checkbox" name="colors" id="yellow"> <label for="yellow">Yellow</label> <br> <br>

            <p>Search Your Country</p>
            <select name="country">
                <option value="bangladesh">Bangladesh</option>
                <option value="pakistan">Pakistan</option>
                <option value="china">China</option>
                <option value="uea">U.E.A</option>
                <option value="dubai">Dubai</option>
                <option value="japan">Japan</option>
                <option value="" selected>Select Your Country</option>
            </select> <br><br>

            <p>Your Range Hare :</p>
            <span>1</span><input type="range" min="1" max="100"><span>100</span> <br> <br>

            <p>Massage Hare :</p>
            <textarea placeholder="Writing-something" name="text_area" cols="40" rows="10"></textarea> <br> <br>

            <button>Submit</button> <button>Cancel</button> <br><br>

            <input type="submit" value="Login" name="" id="">
            <input type="submit" value="Cancel">
            <input type="reset" value="Reset All">
    </form>

    </fieldset>

</body>

</html>
 
 
 # Form-Tag-or-name-registration



https://github.com/user-attachments/assets/ed3daa72-d049-47ba-8bad-930f29d089bd


