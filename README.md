#[ Advanced HTML5 Elements and Forms

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Project - Registration & Contacts</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 0;
            background-color: #f9f9f9;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ccc;
        }
        form {
            background: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            width: 100%;
            max-width: 600px;
        }
        form > div {
            margin-bottom: 15px;
        }
        label {
            display: block;
            font-weight: bold;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .form-section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to Our Contact & Registration Page</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section class="form-section">
        <h2>Topics Covered</h2>
        <ol type="I">
            <li>HTML Structure</li>
            <li>Tables and Forms</li>
            <li>Input Types</li>
            <li>Semantic Elements</li>
            <li>Styling and Layout</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section class="form-section">
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" 
             alt="A beautiful landscape from Pexels" 
             width="100%" style="max-width:700px;">
    </section>

    <!-- Contacts Table -->
    <section class="form-section">
        <h2>Contact List</h2>
        <table>
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
                    <td>Alice Johnson</td>
                    <td>123 Main St, New York</td>
                    <td>+1 212-555-1234</td>
                    <td>alice@example.com</td>
                </tr>
                <tr>
                    <td>Bob Smith</td>
                    <td>456 Maple Ave, Los Angeles</td>
                    <td>+1 310-555-5678</td>
                    <td>bob@example.com</td>
                </tr>
                <tr>
                    <td>Clara Lee</td>
                    <td>789 Oak St, Chicago</td>
                    <td>+1 773-555-9012</td>
                    <td>clara@example.com</td>
                </tr>
                <tr>
                    <td>David Kim</td>
                    <td>321 Pine Rd, Houston</td>
                    <td>+1 832-555-3456</td>
                    <td>david@example.com</td>
                </tr>
                <tr>
                    <td>Eva Martinez</td>
                    <td>654 Elm St, Miami</td>
                    <td>+1 786-555-7890</td>
                    <td>eva@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section class="form-section">
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <!-- Name Field -->
            <div>
                <label for="name">Full Name *</label>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            </div>

            <!-- Email Field -->
            <div>
                <label for="email">Email Address *</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
            </div>

            <!-- Password Field -->
            <div>
                <label for="password">Password *</label>
                <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">
            </div>

            <!-- Date Field -->
            <div>
                <label for="dob">Date of Birth *</label>
                <input type="date" id="dob" name="dob" required>
            </div>

            <!-- Dropdown Menu -->
            <div>
                <label for="country">Country</label>
                <select id="country" name="country" required>
                    <option value="">--Select Country--</option>
                    <option value="usa">United States</option>
                    <option value="uk">United Kingdom</option>
                    <option value="canada">Canada</option>
                    <option value="australia">Australia</option>
                </select>
            </div>

            <!-- Radio Buttons -->
            <div>
                <label>Gender</label>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female" required>
                <label for="female">Female</label>
            </div>

            <!-- Checkboxes -->
            <div>
                <label>Interests</label>
                <input type="checkbox" id="html" name="interests" value="HTML">
                <label for="html">HTML</label>
                <input type="checkbox" id="css" name="interests" value="CSS">
                <label for="css">CSS</label>
                <input type="checkbox" id="js" name="interests" value="JavaScript">
                <label for="js">JavaScript</label>
            </div>

            <!-- Submit Button -->
            <div>
                <button type="submit">Register</button>
            </div>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 HTML Registration Demo</p>
    </footer>

</body>
</html>

Happy Coding! 💻✨
](https://github.com/EMsimeon/desktop-tutorial/blob/c921606b5aae0db3e0649432d92244d38b2b2f8a/python%20week%207)
