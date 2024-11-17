# University Online Quiz and Assignment Submission System

## Project Overview
This web-based platform enables students to take quizzes and submit assignments online. It is built using PHP for server-side logic, HTML for structure, CSS for styling, Bootstrap for responsive design, and jQuery for dynamic and interactive elements. The system allows students to log in, take quizzes, track their scores, and submit assignments.

## Features
- **Student Authentication**: Secure login system for students to access their quizzes and assignments.
- **Online Quizzes**: Students can take quizzes, view questions, and receive instant feedback.
- **Assignment Submission**: Upload and submit assignments through a user-friendly interface.
- **Progress Tracking**: View quiz scores and check the status of submitted assignments.

## Technologies Used
- **PHP**: Server-side scripting to handle user authentication, data storage, and quiz functionality.
- **HTML**: Structure of the website and web pages.
- **CSS**: Custom styles for a clean and modern interface.
- **Bootstrap**: Front-end framework for creating responsive layouts and mobile-friendly design.
- **jQuery**: For adding interactivity, AJAX requests, and DOM manipulation.

## Installation Guide

### Prerequisites
- A web server with PHP support (e.g., XAMPP, WAMP, MAMP, or a live server).
- MySQL or any other relational database.

### Steps to Set Up Locally
1. **Clone the Repository**:
    
2. **Navigate to the Project Folder**:

3. **Setup Local Server**:
    If using XAMPP, move the project folder to the `htdocs` directory.

4. **Create a Database**:
    - Create a MySQL database named `quiz_system`.
    - Import the `database.sql` file (included in the repository) to create necessary tables.

5. **Configure Database Settings**:
    - Open the `config.php` file in the project root directory.
    - Update the database credentials (host, username, password) to match your local environment.

6. **Run the Project**:
    - Start your web server (e.g., Apache in XAMPP).
    - Open a web browser and navigate to:
      ```plaintext
      http://localhost:8080/
      ```

7. **Login and Start Using the System**:
    - Use the login page to sign in as a student.
    - Take quizzes, submit assignments, and track your progress.

## Usage

- **Student Login**: Access the login page, enter credentials, and get redirected to the dashboard.
- **Taking Quizzes**: On the dashboard, students can select available quizzes and begin answering questions.
- **Assignment Upload**: Submit assignments through the assignment submission page by selecting the file to upload.

## Contributing
We welcome contributions! If you have any ideas, bug fixes, or improvements, feel free to fork the repository and submit a pull request.

### Steps to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Open a pull request describing your changes.


## Contact
For further inquiries, please contact the project maintainer at:
- Website: [karthikmp.com](https://karthikmp.com)
