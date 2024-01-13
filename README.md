
Office Management MLM App - README
Welcome to the Office Management MLM App! This application is designed to optimize network marketing in education, providing tools to effortlessly manage teams, enroll students, and streamline course sales. Below, you'll find instructions on setting up, configuring, and running the application.

Table of Contents
Backend Setup
Configure Database
Run CI for Backend
Frontend Setup
Connect Frontend to Backend
Additional Details
Backend Setup
Configure Database 🛠️
Database Installation: Make sure you have a database system like MySQL, PostgreSQL, or MongoDB installed and running on your machine or cloud instance.

Database Configuration:

Navigate to the backend/config folder.
Edit the database configuration file to provide the necessary database connection details such as host, port, username, password, and database name (also do in .env).
Database Initialization:

Run the database migration scripts or commands to create the required tables and schema based on your ORM or database setup.
Run CI for Backend 🚀
Install Dependencies: Navigate to the backend directory and run npm install or yarn install to install all the required backend dependencies.

Run CI Script: Execute the Continuous Integration (CI) script by running the following command:

bash
Copy code
php serve spark
This command will execute the CI pipeline, including linting, testing, and building the backend application.

Frontend Setup
Connect Frontend to Backend 🔗
Navigate to Constants/Api:

Locate the constants folder in your frontend application directory structure.
Edit the configuration file inside this folder (e.g., api.js or config.js).
Update Backend API Endpoint:

Update the backend API endpoint URL to point to your backend server. For example:
javascript
Copy code
const API_ENDPOINT = 'http://localhost:3000/api';
Proxy Setup (Optional):

If you're using a development server like create-react-app, you can set up a proxy in your package.json to forward API requests from the frontend to the backend:
json
Copy code
"proxy": "http://localhost:3000"
Additional Details ℹ️
User Interface: The application comes with a user-friendly interface designed for efficient business operations in MLM education.

Key Features:

Team Creation: Create and manage teams effortlessly.
Enrollment Functions: Streamline student enrollment processes.
Sales Platform: A seamless platform for managing and tracking course sales.
For any further assistance or queries, please refer to the documentation or reach out to our support team.

Thank you for using the Office Management MLM App! 🚀 