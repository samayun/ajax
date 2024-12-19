# ajax example fetch api
Site url: https://samayun.github.io/ajax


This project demonstrates a basic User Management System using vanilla JavaScript, HTML, and CSS. It allows you to perform CRUD operations (Create, Read, Update, Delete) dynamically and fetch mock data from an API.

Features
Fetch and display user data dynamically using the Fetch API.
Create new users.
Edit existing users.
Delete users.
Responsive and clean table design for displaying user information.
Live Demo
Visit Live Site

Algorithm of CRUD Code
Fetch Data (Read Operation)
On clicking the "Load Mock Users" button:
Send an API request to fetch mock user data using the Fetch API.
Parse the JSON response.
Display the first 5 users in a structured table format.
Create Operation
Input user details (Name, Email, Phone) in the form.
On form submission:
Prevent the default behavior of form submission.
Collect the input data and create a new user object.
Add the user object to the users array.
Reset the form and refresh the table to include the new user.
Edit Operation
Click the "Edit" button next to a user in the table.
Populate the form fields with the user’s current data.
Change the "Add User" button text to "Update User".
On form submission:
Update the user object in the users array.
Reset the form, change the button text back to "Add User", and refresh the table.
Delete Operation
Click the "Delete" button next to a user in the table.
Remove the corresponding user object from the users array.
Refresh the table to exclude the deleted user.
How to Run Locally
Clone the repository or download the project files.
Open index.html in any modern web browser.
Interact with the web page to perform CRUD operations.
Technologies Used
HTML5
CSS3
JavaScript (Vanilla)






