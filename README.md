# Lost and Found Management System

This project is a Lost and Found Management System built using Flask, SQLAlchemy, and Bootstrap. It allows users to log in, register items they have found, and search for lost items. The system also provides functionalities for updating and deleting item records.

## Features
- User Authentication (Login and Sign Up)
- Register Found Items
- Search for Lost Items
- Update Item Details
- Delete Item Records

## Project Structure
```plaintext
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
```
## Installation

### Clone the repository:
git clone https://github.com/yourusername/lost-and-found.git
### Navigate to the project directory:
cd lost-and-found
### Create a virtual environment:
python -m venv venv
### Activate the virtual environment:
On Windows: venv\Scripts\activate
On macOS/Linux: source venv/bin/activate
### Install dependencies:
pip install -r requirements.txt
### Run the application:
python app.py
### Usage
Access the app in your browser at http://127.0.0.1:5000.

Pseudocode
```plaintext
Copy code
1. Home Page: Options: Login, Sign Up, Found an Item, Lost an Item  
2. Login Page: Input: Email, Password → Authenticate user  
3. Sign Up Page: Input: Station Name, Email, Password, Confirm Password, Contact Number, Address → Register new station  
4. Enter Item Form: Input: Item Name, Place Found, Date Found, Description → Add to database  
5. View Items Page: Display: Items list → Search, Edit, Delete  
6. Update Item Page: Input: Search query → Display matching items → Actions: Edit/Delete  
7. Edit Item Form: Input: Item details → Update database  
8. Delete Item Function: Remove item from database
