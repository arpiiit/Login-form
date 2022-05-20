# Login-form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My first Webpage</title>
</head>

<body>
    <h1>Registration Form</h1>
    <div id="reg-form">
        <form>
            <label for="first-name">First-name:</label>
            <input type="text" name="first-name" placeholder="FIRST NAME" required>

            <label for="Last-name">Last-name:</label>
            <input type="text" name="Last-name" placeholder="LAST NAME" required>

            <div>
                <label for="gender-male">Male</label>
                <input type="radio" name="gender-choice" value="choice-1">

                <label for="gender-Female">Female</label>
                <input type="radio" name="gender-choice" value="choice-2">

                <label for="gender-other">Other</label>
                <input type="radio" name="gender-choice" value="choice-3">
            </div>

            <div>
                <label for="email">Email</label>
                <input type="email" name="email" placeholder="xyz@gmail.com">

                <label for="Password">Password</label>
                <input type="password" name="Password">
            </div>
            <div>
                <label for="Month">Birthday</label>
                <select name="Month">
                    <option value="0" selected disabled>Month</option>
                    <option value="jan">January</option>
                    <option value="feb">February</option>
                    <option value="march">March</option>
                    <option value="april">April</option>
                    <option value="may">May</option>
                    <option value="june">June</option>
                    <option value="july">July</option>
                    <option value="aug">August</option>
                    <option value="sep">September</option>
                    <option value="oct">october</option>
                    <option value="nov">November</option>
                    <option value="dec">December</option>
                </select>
            </div>
            <label for="agree">I agree to all the conditions of the form </label>
            <input type="checkbox" name="agree" id=""><br>
            <button type="submit">Submit</button>
        </form>


    </div>
</body>

</html>
