# Logging-Page-01.


<!DOCTYPE html>
<html lang="en">
<head>
    <title>Sign Up Form</title>
</head>
<style>

* {
  box-sizing: border-box;
}

body {

background:url(https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg?auto=compress&cs=tinysrgb&w=600)no-repeat center center/cover;
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.5;
  background-color: #f7f8fa;
}

form {
  max-width: 600px;
  margin: 50px auto;
  padding: 30px 40px;
  background: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

form h1 {
  max-width: 600px;
  margin: 50px auto;
  padding: 30px 40px;
  background: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
.form-container {
  background-color: #fff;
  width: 400px;
  padding: 25px 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.15);
}
.input-row {
  display: flex;
  gap: 10px;
  margin-bottom: 12px;
}
.input-row input,
.input-row select {
  flex: 1;
  padding: 10px;
  font-size: 14px;
  border: 1px solid #ccd0d5;
  border-radius: 6px;
}
.input-row input[type="text"],
.input-row input[type="email"],
.input-row input[type="password"],
.input-row input[type="number"],
.input-row input[type="date"],
.input-row input[type="time"],
.input-row input[type="color"],
.input-row input[type="file"],
.input-row select,



.input-row textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}
.input-row input[type="text"]:focus,
.input-row input[type="email"]:focus,
.input-row input[type="password"]:focus,

.input-row input[type="number"]:focus,
.input-row input[type="date"]:focus,
.input-row input[type="time"]:focus,
.input-row input[type="color"]:focus,
.input-row input[type="file"]:focus,
.input-row select:focus,
.input-row textarea:focus {
  border-color: #007bff;
  outline: none;
}
.input-row input[type="text"],
.input-row input[type="email"],
.input-row input[type="password"],
.input-row input[type="number"],
.input-row input[type="date"],
.input-row input[type="time"],
.input-row input[type="color"],
.input-row input[type="file"],
.input-row select,

.input-row textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}
.input-row select {
  flex: 1;
  padding: 10px;
  font-size: 14px;
  border: 1px solid #ccd0d5;
  border-radius: 6px;
}

.form-container h2 {
 text-align: center;
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 5px;
  margin: 0 0 20px;
  text-align: center;
  font-size: 1.5em;
  font-weight: 700;
  color: #333;
}
.form-container p {
 text-align: center;
  font-size: 14px;
  color: #606770;
  margin-bottom: 20px;
  text-align: center;
  font-size: 1em;
  color: #666;
}
.form-container input[type="text"],
.form-container input[type="email"],
.form-container input[type="password"],
.form-container input[type="number"],
.form-container input[type="date"],
.form-container input[type="time"],
.form-container input[type="color"],
.form-container input[type="file"],
.form-container select,
.form-container textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}

.form-container input[type="text"],
.form-container input[type="email"],
.form-container input[type="password"],
.form-container input[type="number"],
.form-container input[type="date"],
.form-container input[type="time"],
.form-container input[type="color"],
.form-container input[type="file"],
.form-container select,
.form-container textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}
.full-width input {
  width: 100%;
  padding: 10px;
  font-size: 14px;
  border: 1px solid #ccd0d5;
  border-radius: 6px;
}
gender-row {
  display: flex;
  justify-content: space-between;
  margin-bottom: 12px;
}

.gender-row label {
  flex: 1;
  text-align: center;
  background-color: #f5f6f7;
  padding: 8px 0;
  border: 1px solid #ccd0d5;
  border-radius: 6px;
  font-size: 14px;
  cursor: pointer;
  position: relative;
}

.gender-row input[type="radio"] {
  position: absolute;
  top: 10px;
  left: 10px;
}

.policy {
  font-size: 11px;
  color: #777;
  margin-bottom: 12px;
  line-height: 1.4;
}
.policy a {
  color: #385898;
  text-decoration: none;
}

.policy a:hover {
  text-decoration: underline;
}


utton.signup-btn {
  width: 100%;
  padding: 10px;
  background-color: #42b72a;
  color: white;
  font-weight: bold;
  font-size: 16px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  margin-bottom: 12px;
}

button.signup-btn:hover {
  background-color: #36a420;
}


.footer-link h1{
  text-align: center;
  font-size: 14px;
}

.footer-link a {
  color: #1877f2;
  text-decoration: none;
}

.footer-link a:hover {
  text-decoration: underline;
}

.form-container input[type="text"]:focus,
.form-container input[type="email"]:focus,
.form-container input[type="password"]:focus,
.form-container input[type="number"]:focus,
.form-container input[type="date"]:focus,
.form-container input[type="time"]:focus,
.form-container input[type="color"]:focus,
.form-container input[type="file"]:focus,
.form-container select:focus,


.form-container textarea:focus {
  border-color: #007bff;
  outline: none;
}

.form-container h1 {
  margin: 0 0 20px;
  text-align: center;
  font-size: 2em;
  font-weight: 700;
  color: #ec7c7c;
  border-bottom: 2px solid #eee;
  padding-bottom: 10px;
}
.form-container h2 {
  margin: 0 0 20px;
  text-align: center;
  font-size: 1.5em;
  font-weight: 700;
  color: #333;
}
.form-container p {
  text-align: center;
  font-size: 1em;
  color: #666;
}
.form-container input[type="text"],
.form-container input[type="email"],
.form-container input[type="password"],
.form-container input[type="number"],
.form-container input[type="date"],
.form-container input[type="time"],
.form-container input[type="color"],
.form-container input[type="file"],
.form-container select,
.form-container textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}


.form-container input[type="text"]:focus,
.form-container input[type="email"]:focus,
.form-container input[type="password"]:focus,
.form-container input[type="number"]:focus,
.form-container input[type="date"]:focus,
.form-container input[type="time"]:focus,
.form-container input[type="color"]:focus,
.form-container input[type="file"]:focus,
.form-container select:focus,
.form-container textarea:focus {
  border-color: #007bff;
  outline: none;
}
.form-container input[type="submit"],
.form-container input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container input[type="submit"] {
  background-color: #28a745;
}   

.form-container input[type="reset"] {
  background-color: #dc3545;
}
.form-container input[type="submit"]:hover {
  background-color: #218838;
}   
.form-container input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container input[type="checkbox"] {
  margin-right: 5px;
  vertical-align: middle;
}
.form-container label {
  display: block;
  margin-bottom: 10px;
  font-weight: 600;
  color: #555;
}
.form-container .options {
  display: flex;
  gap: 20px;
}
.form-container .options label {
  flex: 0 0 auto;
  font-weight: normal;
}
.form-container input[type="radio"],
.form-container input[type="checkbox"] {
  margin-right: 5px;
  vertical-align: middle;
}
.form-container .button-row {
  text-align: center;
  margin-top: 25px;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}

.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}

.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}

.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}


.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],


.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}

.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}


.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-container .button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}
.form-container .button-row input[type="submit"] {
  background-color: #28a745;
}
.form-container .button-row input[type="reset"] {
  background-color: #dc3545;
}
.form-container .button-row input[type="submit"]:hover {
  background-color: #218838;
}
.form-container .button-row input[type="reset"]:hover {
  background-color: #c82333;
}
.form-container .button-row input[type="submit"],
.form-row {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 15px;
  align-items: center;
}

.form-row label {
  flex: 0 0 140px;
  margin-right: 10px;
  font-weight: 600;
  color: #555;
}

.form-row input[type="text"],
.form-row input[type="email"],
.form-row input[type="password"],
.form-row input[type="number"],
.form-row input[type="date"],
.form-row input[type="time"],
.form-row input[type="color"],
.form-row input[type="file"],
.form-row select,
.form-row textarea {
  flex: 1 1 0;
  padding: 8px 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  color: #333;
}

.form-row textarea {
  min-height: 100px;
  resize: vertical;
}

.form-row .options {
  display: flex;
  gap: 20px;
}

.form-row .options label {
  flex: 0 0 auto;
  font-weight: normal;
}

.form-row input[type="radio"],
.form-row input[type="checkbox"] {
  margin-right: 5px;
  vertical-align: middle;
}

.button-row {
  text-align: center;
  margin-top: 25px;
}

.button-row input[type="submit"],
.button-row input[type="reset"] {
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
  padding: 10px 25px;
  border: none;
  border-radius: 4px;
  color: #fff;
  margin: 0 10px;
  transition: background-color 0.2s ease;
}

.button-row input[type="submit"] {
  background-color: #28a745;
}

.button-row input[type="reset"] {
  background-color: #dc3545;
}

.button-row input[type="submit"]:hover {
  background-color: #218838;
}

.button-row input[type="reset"]:hover {
  background-color: #c82333;
}

@media (max-width: 600px) {
  .form-row {
    flex-direction: column;
    align-items: stretch;
  }
  .form-row label {
    margin-bottom: 5px;
    width: auto;
  }
  .button-row input {
    width: 100%;
    margin: 10px 0;
  }
}





      </style>

<body>
    <div class="container">
        <h1>Loging Page</h1>
        <h2>Create a New Account</h2>
        <p>It's quick and easy.</p>

        <form>
            <label for="first-name">First Name</label>
            <input type="text" id="first-name" placeholder="First Name" required><br>

            <label for="last-name">Last Name</label> <input type="text" id="last-name" placeholder="Last Name" required><br>
            <label for="password">New Password</label> <input type="password" id="password" placeholder="New Password" required><br>

            <label for="dob">Date of Birth</label> <input type="date" id="dob" required><br>

            <label for="email">Mobile number or E-mail Address</label> <input type="email" id="email" placeholder="Email or Phone Number" required><br>
            <label for="confirm-password">Confirm Password</label> <input type="password" id="confirm-password" placeholder="Confirm Password" required><br>
           <select name="code">
            <option value="880">880</option>
            <option value="110">110</option>
            <option value="990">990</option>
           </select>
           <input type="number" id="number" placeholder="Number" value="01797-921564"> <br>
           <label for="country">Country</label>
           <input list="con"id="country">
            <datalist id="con">
                <option value="Bangladesh">
                <option value="India">
                <option value="Pakistan">
                <option value="Nepal">
                <option value="Bhutan">
            </datalist><br>

            <select id="year" required><br>
                <option value="">Year</option>
                <option value="2000">2000</option>
                <option value="1999">1999</option>
                <option value="1998">1998</option>
            </select>

            <select id="month" required><br>
                <option value="">Month</option>
                <option value="1">January</option>
                <option value="2">February</option>
                <option value="3">March</option>
            </select>

            <select id="day" required><br>
                <option value="">Day</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
            </select>

            <select id="country" required><br>
                <option value="">Select Country</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
            </select><br>


            <label for="gender">Gender</label>
            <select id="gender" required><br>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            Gender:-
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
            <label for="date-of-birth">Date of Birth</label><br>
            <input type="date" id="date-of-birth" name="date-of-birth" required><br>
            <label for ="Time">Time</label><br>
            <input type="time" id="Time" name="Time" required><br>
            <label for="color">Chose Color:-</label>
            <input type="color" id="color" name="color" required><br>
            <label for="File">Upload File</label>
            <input type="file" id="file" name="file" accept=".jpg, .png, .gif" required><br>
            <label for="photo">Your Photo:-</label>
            <input type="file" id="photo" name="photo" accept=".jpg, .png, .gif" required><br>
            <textarea rows="5" cols="20" placeholder="Write something..." required></textarea><br>
            <label for="checkbox" id="checkbox">I agree to the terms and conditions</label>
            <input type="checkbox" id="checkbox" name="checkbox" required><br>
            <label for="laptop">I Have a Laptop</label>
            <input type="checkbox" id="laptop" name="laptop"><br>
            <input type="Submit" value="Send">
            <input type="reset" value="Reset">
          
            <button type="submit">Sign Up</button>
        </form>
    </div>
</body>
</html>
