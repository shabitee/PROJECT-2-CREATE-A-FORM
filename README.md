<!DOCTYPE html>
<html>
<head>
<title>Registration Form</title>
<meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="styles.css" /> 
</head>
<main>
    <body>
<h1>Registration Form</h1>
<br/><br/>
<article class="zero">
<form action="">
    <label for="fname">First Name</label><br/>
    <input type="text" id="fname" name="fname" required>
</form><br/>
</article>
<article class="one">
    <form action="">
        <label for="lname">Surname</label><br/>
        <input type="text" id="lname" name="Surname" required>
    </form><br/><br/>
    </article>
    <article class="two">
        <form action="">
            <label for="email">Email</label><br/>
            <input type="email" id="email" name="Email"><br/><br/>
        </form>
    </article>
    <article class="three">
        <p>Where did you find Us?</p>
        <button type="button">Instagram</button>
        <button type="button">Facebook</button>
        <button type="button">Google</button>
    </article><br/><br/>
    <article c;ass="four">
        <label for="contact type">How do you want us to contact you:</label>
        <select name="contact type" id="contact type">
            <option value="email">Email</option>
            <option value="mobile">Mobile</option>
            <option value="post">Post</option>
        </select>
    </article>
    <input type="submit" value="Submit">
    <article class="five"><br>
        
        <form action="">
            <label for="rating">How would you rate us?</label><br>
            <input type="checkbox" id="feedback1" name="feedback1" value="1">
            <label for="feedback1"> 1</label><br>
            <input type="checkbox" id="feedback2" name="feedback2" value="2">
            <label for="feedback3"> 2</label><br>
            <input type="checkbox" id="feedback3" name="feedback3" value="3">
            <label for="feedback1"> 3</label><br>
            <input type="checkbox" id="feedback4" name="feedback4" value="4">
            <label for="feedback1"> 4</label><br>
            <input type="checkbox" id="feedback1" name="feedback1" value="5">
            <label for="feedback1"> 5</label><br>
            <input type="submit" value="Submit">


        </form>
    </article>
</body>
<footer>
    <p>By: Taiwo Bidmos<p>
    <p>Copyright 2022</p>    

</footer>
</html>

</main>
