<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    fieldset {
      margin-bottom: 20px;
    }

    legend {
      font-weight: bold;
      font-size: 1.2em;
    }

    label {
      display: block;
      margin-bottom: 5px;
    }

    input {
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
      margin-bottom: 10px;
    }
  </style>
  <title>My Resume</title>
</head>

<body>
  <h1>Rohit's Resume</h1>
  <fieldset>
    <legend>Contact Information</legend>
    <label for="Full Name">Full Name</label>
    <input type='text' id='Full Name' name='Full Name'>
    <label for="Email">Email address</label>
    <input type='text' id='Email' name='Email'>
    <label for='Phone.no'>Phone Number</label>
    <input type='tel' id='Phone.no' name='Phone.no'>
  </fieldset>
  <fieldset>
    <legend>Education</legend>
    <label for="Graduation">Graduation</label>
    <textarea name='Graduation' id='Graduation' rows=3>
    </textarea>
    <label for='Inter'>Secondary Education</label>
    <textarea id='Inter' name='Inter' rows=3></textarea>
    <label for='SSC'>SSC</label>
    <textarea id='SSC' name='SSC' rows='3'></textarea>
  </fieldset>
  <fieldset>
    <legend>Projects</legend>
    <label for='Name1'>Name:</label>
    <textarea name='Name1' id='Name1' rows=3></textarea>
    <label for='Name2'>Name:</label>
    <textarea name='Name2' id='Name2' rows=3></textarea>
  </fieldset>
  <fieldset>
    <legend>Certifications</legend>
    <textarea id='Certifications' name='Certifications' rows=5></textarea>
  </fieldset>
  <fieldset>
    <label for='Languages'>Languages</label>
    <input type='text' id='text' name='text'>
  </fieldset>
  <button type='submit'>submit</button>
</body>

</html>
