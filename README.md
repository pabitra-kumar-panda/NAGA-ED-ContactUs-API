# NAGA-ED-ContactUs-API
# Contact Us Form

A simple "Contact Us" form built using HTML, CSS, and JavaScript. The form includes fields for name, email, and message, with basic input validation. Upon successful submission, a confirmation message is displayed, and the input data is logged to the browser console.

# Features
1) Input fields for:
   Name,
   Email,
   Message
2) Input validation:
   All fields are required,
   Valid email format is checked.
3) Display of a success message upon form submission 
   Logs submitted form data to the browser's console,
   Responsive design for better user experience.
4) Technology Stack
   HTML (ContactUs.html),
   CSS (ContactUs.css),
   JavaScript (Contact.js)
# Open ContactUs file------>ContactUs.html to use the page.

# Course-API
A simple RESTful API built with Node.js and Express that allows for CRUD (Create, Read, Update, Delete) operations on courses.

# Features
  Create a new course,
  Read a list of courses,
  Update an existing course,
  Delete a course
# Technology Stack
  Node.js,
  Express.js
# Prerequisites
  Make sure you have Node.js and npm installed on your machine. LINK- (https://nodejs.org/en)
# Method to Run the API
  1) Clone the repository 
  2) Navigate into the project directory (cd course-api)
  3) Install dependencies: Run the following command to install all necessary dependencies, including Express.js (npm install)
  4) Start the server: After installing the dependencies, start the server with (node server.js)
  5) The server should be running at http://localhost:3000/

# Use POSTMAN to test the API
  # Add a new course. Make sure to include the required fields in the request body (title, description, duration).
   
  1) Create New HTTP-------->Add operation (POST) for adding data---------->Paste the server link http://localhost:3000/courses----------->Add the data to the body
{
  "title": "Intro to Programming",
  "description": "Learn the basics of programming.",
  "duration": "6 weeks"
} -------------->Send-------->the data will get added.

  2) Add operation (GET) for reading all the present data---------------> Paste the server link http://localhost:3000/courses-------------------->Send--------> You will see all the data present

  3) Add operation (PUT) to update-------------------> Paste the server link http://localhost:3000/courses/:i (add the id at (:i) you wanna update)----------------> Add the updated data to the body {
  "title": "Advanced Programming",
  "description": "Learn advanced programming concepts.",
  "duration": "8 weeks"
}---------->Send--------> The data gets updated
 
  4) Add operation (DELETE) to delete--------------->Paste the server link http://localhost:3000/courses/:i (add the id at (:i) you wanna delete)--------------->Send-------->Data gets deleted





















