<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Registration</title>
  <style>
    body {
      background-color: lightblue;
      font-family: Arial, sans-serif;
      margin: 30px;
    }

    form {
      background-color: #d1ef7d; /* light green form background */
      padding: 30px;
      border-radius: 10px;
      width: 80%;
      margin: auto;
      box-shadow: 0px 0px 10px gray;
    }

    table, th, td {
      border: 1px solid #06cd4c;
      border-collapse: collapse;
      padding: 10px;
      background-color: #ecffcc;
      text-align: center;
    }

    th {
      background-color: #b7ffb7;
    }

    h1, h4 {
      text-align: center;
    }

    label {
      font-weight: bold;
    }

    input[type="text"], input[type="date"], textarea, input[type="file"] {
      width: 50%;
      padding: 5px;
      margin: 5px 0;
    }

    .center-button {
      text-align: center;
      margin-top: 20px;
    }

    button {
      padding: 10px 20px;
      background-color: green;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 16px;
      border-radius: 5px;
    }

    button:hover {
      background-color: darkgreen;
    }
  </style>
</head>
<body>

  <h1><u>Student Registration</u></h1>

  <form>
    <fieldset>
      <label for="fname">First Name:</label><br>
      <input type="text" id="fname" name="fname" placeholder="First Name" required><br><br>

      <label for="lname">Last Name:</label><br>
      <input type="text" id="lname" name="lname" placeholder="Last Name" required><br><br>

      <label for="dob">Date of Birth:</label><br>
      <input type="date" id="dob" name="dob" required><br><br>

      <h4>Gender:</h4>
      <input type="radio" name="gender" id="male" value="male">
      <label for="male">Male</label>
      <input type="radio" name="gender" id="female" value="female">
      <label for="female">Female</label><br><br>

      <label for="address">Address:</label><br>
      <textarea id="address" name="address" rows="3" maxlength="100" placeholder="Enter your address"></textarea><br><br>

      <label for="state">State:</label><br>
      <input type="text" id="state" name="state"><br><br>

      <label for="district">District:</label><br>
      <input type="text" id="district" name="district"><br><br>

      <label for="city">City:</label><br>
      <input type="text" id="city" name="city"><br><br>

      <label for="village">Village:</label><br>
      <input type="text" id="village" name="village"><br><br>

      <label for="pincode">Pincode:</label><br>
      <input type="text" id="pincode" name="pincode" maxlength="6"><br><br>

      <label for="email">Email:</label><br>
      <input type="text" id="email" name="email"><br><br>

      <label for="phno">Phone Number:</label><br>
      <input type="text" id="phno" name="phno" maxlength="10"><br><br>

      <h2>Qualification Details</h2>
      <table width="100%">
        <tr>
          <th>SI NO</th>
          <th>Qualification</th>
          <th>Name of the Board</th>
          <th>Marks Obtained</th>
          <th>Year of Passing</th>
          <th>Percentage</th>
        </tr>
        <tr>
          <td>1</td>
          <td><input type="text" name="qual1"></td>
          <td><input type="text" name="board1"></td>
          <td><input type="text" name="marks1"></td>
          <td><input type="text" name="year1"></td>
          <td><input type="text" name="percent1"></td>
        </tr>
        <tr>
          <td>2</td>
          <td><input type="text" name="qual2"></td>
          <td><input type="text" name="board2"></td>
          <td><input type="text" name="marks2"></td>
          <td><input type="text" name="year2"></td>
          <td><input type="text" name="percent2"></td>
        </tr>
        <tr>
          <td>3</td>
          <td><input type="text" name="qual3"></td>
          <td><input type="text" name="board3"></td>
          <td><input type="text" name="marks3"></td>
          <td><input type="text" name="year3"></td>
          <td><input type="text" name="percent3"></td>
        </tr>
      </table><br>

      <label for="resume">Upload Resume:</label><br>
      <input type="file" id="resume" name="resume"><br><br>

      <div class="center-button">
        <button type="submit">Submit</button>
      </div>
    </fieldset>
  </form>

</body>
</html>
