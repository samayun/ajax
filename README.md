# ajax example fetch api
Site url: https://samayun.github.io/ajax


This project demonstrates a basic **User Management System** using vanilla JavaScript, HTML, and CSS. It allows you to perform CRUD operations (Create, Read, Update, Delete) dynamically and fetch mock data from an API.

## Features

- Fetch and display user data dynamically using the **Fetch API**.
- Create new users.
- Edit existing users.
- Delete users.
- Responsive and clean table design for displaying user information.

## Live Demo

[Visit Live Site](https://samayun.github.io/ajax/)

## Algorithm of CRUD Code

### **Fetch Data (Read Operation)**

1. On clicking the "Load Mock Users" button:
   - Send an API request to fetch mock user data using the Fetch API.
   - Parse the JSON response.
   - Display the first 5 users in a structured table format.

### **Create Operation**

1. Input user details (Name, Email, Phone) in the form.
2. On form submission:
   - Prevent the default behavior of form submission.
   - Collect the input data and create a new user object.
   - Add the user object to the `users` array.
   - Reset the form and refresh the table to include the new user.

### **Edit Operation**

1. Click the "Edit" button next to a user in the table.
2. Populate the form fields with the user’s current data.
3. Change the "Add User" button text to "Update User".
4. On form submission:
   - Update the user object in the `users` array.
   - Reset the form, change the button text back to "Add User", and refresh the table.

### **Delete Operation**

1. Click the "Delete" button next to a user in the table.
2. Remove the corresponding user object from the `users` array.
3. Refresh the table to exclude the deleted user.

## How to Run Locally

1. Clone the repository or download the project files.
2. Open `index.html` in any modern web browser.
3. Interact with the web page to perform CRUD operations.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
