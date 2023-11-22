# Bulletin-Board-using-React.js

# Project Overview:  
This project is a bulletin board system developed for the National Government, aimed at facilitating the sharing of important issues and information through posts. The system includes features for user registration, login, post-creation, deletion, and retrieval. It's built with security in mind, utilizing SSL for all API calls, implementing proper Cross-Origin Resource Sharing (CORS), and securely storing and comparing passwords using bcrypt.

# How to Install and Run the Project:
(Visual Studio Code)

(Prerequisites)
Node.js and npm: Install Node.js and npm on your machine. You can download them from https://nodejs.org/.

(Project Setup)
- Clone the Repository: Clone this repository to your local machine using Git or download the project as a ZIP file and extract it.

- Navigate to the Project Directory: Open your terminal and navigate to the project directory.

- Install Dependencies: Run the following command to install the project dependencies: npm install

- Start the Server: Once the configuration is set up, start the server by running the following command: npm run dev.

# App features
(Version 1.1)
- User Registration and Login: Users can register for an account and log in securely. Passwords are hashed using bcrypt for security.

- Create, Retrieve, and Delete Posts: Users can create new posts, view existing posts, and delete their own posts.

- Secure Communication: All API calls are made over SSL to ensure the security and privacy of user data.

- CORS Support: Cross-Origin Resource Sharing (CORS) is implemented to allow the application to be accessed from different domains.

- Route Separation: The API has separate routes for handling user-related operations and post-related operations. These routes are protected to ensure secure access.

- Session Persistence: User login information is persisted after authentication, allowing users to stay logged in.

Additional Notes ~
If you encountered issues with npm i bcrypt, note that there might be compatibility or installation issues with bcrypt. In my project, I used bcryptjs as an alternative library for password hashing. This should work for you without any issues.
Thank you for using the National Government Bulletin Board system. If you have any questions or need further assistance, please feel free to reach out.

# Error features:  
npm i bcrypt would not work so I had to install bcrypjs to hash the password.

