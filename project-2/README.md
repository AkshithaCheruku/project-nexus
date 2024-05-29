# Simple Restaurant Website Login and Signup Authentication
![Screenshot 2024-05-29 200206](https://github.com/AkshithaCheruku/project-nexus/assets/78154074/86b053f0-2709-407e-afd6-34fee3b592ac)

![Screenshot 2024-05-29 201504](https://github.com/AkshithaCheruku/project-nexus/assets/78154074/11f7175f-4062-4892-894a-41bc2bf3af9c)

![Screenshot 2024-05-29 201544](https://github.com/AkshithaCheruku/project-nexus/assets/78154074/d807938f-d842-4efa-80b3-ef061caa473f)

# A Deep Dive into Creating a MERN App with Login and Signup
In this project, we’ll use MongoDB, Express, React, and Node.js to build a web app that lets users log in and register. We’ll make sure it’s safe and easy to use by adding JWT authentication to protect user data.





# Design and User Experience
With a focus on login app design, the front-end features a React login page template that is not only functional but also aesthetically pleasing. This application is not just an authentication MERN stack demonstration but also a testament to thoughtful design in creating engaging user interfaces.

# Authentication 
I utilized JWTs (JSON Web Tokens) to manage sessions and secure user data, providing a reliable and robust auth MERN structure.

# MERN Authentication JWT
Incorporating mern authentication JWT within this MERN stack application example ensures that the tokens used for user sessions are managed according to the latest security standards. It's a critical feature that underscores the entire authentication process in my MERN application example.

# Features
- User Registration: Allows new users to create an account.
- User Login: Enables users to log in with their credentials.
- JWT Authentication: Secures user sessions using JSON Web Tokens.
- Responsive Design: Ensures a great user experience across various devices.

# Technologies Used
Frontend:
- React.js: For building the user interface.
- Toastify: To display notifications and alerts.
- React Router DOM: For managing navigation in the application.
Backend:
- Node.js: As the runtime environment.
- Express: Web application framework for Node.js.
- MongoDB: Database to store user credentials and session data.

# Installation
1. Clone the repository:
git clone https://github.com/AkshithaCheruku/project-nexus.git


2. Install dependencies:
Navigate to the project directory:
cd folder-name


3. Install backend dependencies:
npm install


4. Install frontend dependencies:
cd client
npm install

5. Configure MongoDB and JWT:
Visit MongoDB website, create account, database and take connection string.
After that generating 256 bits random key and add it to .env file.
Create the .env file in the root directory with the following contents:

MONGO_URI= your mongodb uri
JWT_SECRET=your jwt secret key


6. Run the application:
Start the backend server:
node app.js

7. In a new terminal, start the frontend:
cd client
npm run dev


