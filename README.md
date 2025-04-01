# index.htmlV
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form & Contacts</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
    </style>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>Steps to Register</h2>
    <ol type="I">
        <li>Fill in the form</li>
        <li>Agree to terms</li>
 <li>Submit your details</li>
        <li>Check your email</li>
        <li>Complete verification</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Sample Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Pexels Sample" width="400">

    <!-- Table with 5 Contacts -->
    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>Nairobi, Kenya</td>
            <td>+254 712 345678</td>
            <td>johndoe@gmail.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>Mombasa, Kenya</td>
            <td>+254 733 987654</td>
            <td>janesmith@gmail.com</td>
        </tr>
        <tr>
            <td>Kevin Mwangi</td>
            <td>Kisumu, Kenya</td>
            <td>+254 721 112233</td>
            <td>kevinmwangi@gmail.com</td>
        </tr>
        <tr>
            <td>Linda Wanjiru</td>
            <td>Nakuru, Kenya</td>
            <td>+254 700 445566</td>byj
            <td>lindawanjiru@gmail.com</td>
        </tr>
        <tr>
            <td>Brian Otieno</td>
            <td>Eldoret, Kenya</td>
 <td>+254 722 778899</td>
            <td>brian@example.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="submit.php" method="POST">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required>
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown -->
        <label for="country">Select Country:</label>
        <select id="country" name="country">
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required> <label for="male">Male</label>
 <input type="radio" id="female" name="gender" value="female"> <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other"> <label for="other">Other</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interests" value="coding"> <label for="coding">Coding</label>
        <input type="checkbox" id="music" name="interests" value="music"> <label for="music">Music</label>
        <input type="checkbox" id="sports" name="interests" value="sports"> <label for="sports">Sports</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>
```
