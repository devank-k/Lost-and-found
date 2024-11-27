<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lost and Found Management System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #66fcf1 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .main {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
        }
        .main h1 {
            text-align: center;
            color: #333;
        }
        .main p {
            text-align: justify;
        }
        .main pre {
            background: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Lost and Found Management System</h1>
        </div>
    </header>
    <div class="container main">
        <h1>Introduction</h1>
        <p>
            This project is a Lost and Found Management System built using Flask, SQLAlchemy, and Bootstrap. 
            It allows users to log in, register items they have found, and search for lost items. 
            The system also provides functionalities for updating and deleting item records.
        </p>

        <h1>Features</h1>
        <ul>
            <li>User Authentication (Login and Sign Up)</li>
            <li>Register Found Items</li>
            <li>Search for Lost Items</li>
            <li>Update Item Details</li>
            <li>Delete Item Records</li>
        </ul>

        <h1>Project Structure</h1>
        <pre>
app.py
templates/
    base.html
    index.html
    login.html
    signup.html
    enteritem.html
    viewitem.html
    updateitem.html
    edit_item.html
static/
    style.css
        </pre>

        <h1>Installation</h1>
        <p>To run this project locally, follow these steps:</p>
        <pre>
1. Clone the repository:
   git clone https://github.com/yourusername/lost-and-found.git

2. Navigate to the project directory:
   cd lost-and-found

3. Create a virtual environment:
   python -m venv venv

4. Activate the virtual environment:
   - On Windows: venv\Scripts\activate
   - On macOS/Linux: source venv/bin/activate

5. Install the required dependencies:
   pip install -r requirements.txt

6. Run the application:
   python app.py
        </pre>

        <h1>Usage</h1>
        <p>Once the application is running, you can access it in your web browser at <a href="http://127.0.0.1:5000">http://127.0.0.1:5000</a>.</p>
        <ul>
            <li>Home Page: Provides options to log in, sign up, register found items, and search for lost items.</li>
            <li>Login Page: Allows users to log in with their email and password.</li>
            <li>Sign Up Page: Allows new users to register by providing their details.</li>
            <li>Enter Item Form: Allows logged-in users to register items they have found.</li>
            <li>View Items Page: Displays a list of registered items and provides options to search, edit, or delete items.</li>
            <li>Update Item Page: Allows users to search for items and update their details.</li>
            <li>Edit Item Form: Allows users to edit the details of a specific item.</li>
        </ul>

        <h1>Block Diagram</h1>
        <p>The block diagram of the project is as follows:</p>
        <img src="block_diagram.png" alt="Block Diagram" style="width:100%;">

        <h1>Pseudocode</h1>
        <p>The pseudocode for the project is as follows:</p>
        <pre>
1. Home Page
   - Display options: Login, Sign Up, Found an Item, Lost an Item
2. Login Page
   - Input: Email, Password
   - Action: Authenticate user
3. Sign Up Page
   - Input: Station Name, Email, Password, Confirm Password, Contact Number, Address
   - Action: Register new station
4. Enter Item Form
   - Input: Item Name, Place Found, Date Found, Description
   - Action: Add new item to the database
5. View Items Page
   - Display: List of items
   - Actions: Search items, Edit item, Delete item
6. Update Item Page
   - Input: Search query
   - Display: List of items matching the search query
   - Actions: Edit item, Delete item
7. Edit Item Form
   - Input: Item details
   - Action: Update item details in the database
8. Delete Item Function
   - Action: Remove item from the database
        </pre>

        <h1>Contributing</h1>
        <p>Contributions are welcome! Please feel free to submit a Pull Request.</p>

        <h1>License</h1>
        <p>This project is licensed under the MIT License.</p>
    </div>
    <footer>
        <p>Lost and Found Management System &copy; 2023</p>
    </footer>
</body>
</html>
