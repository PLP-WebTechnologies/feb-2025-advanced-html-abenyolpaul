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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My HTML Page</title>
</head>
<body>
    <h1>Welcome to My Page</h1>

    <!-- Ordered list with roman numerals -->
    <h2>Top 5 Favorite Books</h2>
    <ol type="I">
        <li>To Kill a Mockingbird</li>
        <li>1984</li>
        <li>The Great Gatsby</li>
        <li>Pride and Prejudice</li>
        <li>The Catcher in the Rye</li>
    </ol>

    <!-- External image from pexels.com -->
    <h2>Beautiful Nature</h2>
    <img src="https://images.pexels.com/photos/417074/pexels-photo-417074.jpeg" 
         alt="Mountain landscape" 
         width="600"
         style="max-width: 100%; height: auto;">

    <!-- Table of contacts -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="8" cellspacing="0">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Smith</td>
                <td>123 Main St, Anytown</td>
                <td>(555) 123-4567</td>
                <td>john.smith@example.com</td>
            </tr>
            <tr>
                <td>Sarah Johnson</td>
                <td>456 Oak Ave, Somewhere</td>
                <td>(555) 234-5678</td>
                <td>sarah.j@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Pine Rd, Nowhere</td>
                <td>(555) 345-6789</td>
                <td>m.brown@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>321 Elm Blvd, Anycity</td>
                <td>(555) 456-7890</td>
                <td>emily.d@example.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>654 Maple Ln, Yourtown</td>
                <td>(555) 567-8901</td>
                <td>dwilson@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <div>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>
        </div>
        <br>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </div>
        <br>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required minlength="8">
        </div>
        <br>
        <div>
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone">
        </div>
        <br>
        <div>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob">
        </div>
        <br>
        <div>
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="">Select</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
                <option value="prefer-not">Prefer not to say</option>
            </select>
        </div>
        <br>
        <div>
            <input type="checkbox" id="terms" name="terms" required>
            <label for="terms">I agree to the terms and conditions</label>
        </div>
        <br>
        <div>
            <button type="submit">Register</button>
            <button type="reset">Reset</button>
        </div>
    </form>
</body>
</html>
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
