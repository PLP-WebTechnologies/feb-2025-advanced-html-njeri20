# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html>
 <head>
  <title>Multimedia Webpage</title>
 </head>
 <body>
  <h1>Welcome to Our Multimedia Page</h1>
  <h2>Audio Example</h2>
  <audio controls>
   <source src="" type="">
   <source src="" type="">
  </audio>
<h2>Video Example</h2>
  <video controls width="640" height"360">
   <source src="" type "">
   <source src="" type="">
 </body>
</html>


<!DOCTYPE html>
<html>
 <head>
  <title> Registration Form</title>
 </head>
 <body>
  <h2> Registration</h2>
  <form action="/submit_registration" method="post">
   <div>
    <label for="username">Username:</label>
    <input type="texc" id="username" name="username" required minlength="5" maxlenght="20">
    <small> Username must be betweeen 5 and 20 characters</small>
   </div>

   <div>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    <small> Please enter a valid email address.</small>
   </div>
<div>
 <label for="password">Password:</label>
 <input type="password" id="password" name="password" required minlength="8">
 <small> Password must be at least 8 characters long.</small>
</div>
<div>
 <label for="confirm_password">Confirm Password:</label>
 <input type="password" id="confirm_password" name="confirm_password" required minlength="8">
 <small> Password must match.</small>
</div>
<div>
 <label for="age">Age:</label>
 <input type="number" id="age" name="age" min="13" max="100">
 <small> You must be at least 13 years old to register.</small>
</div>

<div>
 <label for="country">Country:</label>
 <select id="country" name="country" required>
  <option value="">Select Country</option>
  <option value="Ke">Kenya</option>
  <option value="Ug">Uganda</option>
  <option value="Tz">Tanzania</option>
 </select>
 <div>
  <label for="terms">I agree to the terms and conditions:</label>
  <input type="checkbox" id="terms" name="terms" required>
 </div>
 <button type="submit">Register</button>
</form>
 </body>
</html>





