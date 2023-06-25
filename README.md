Secrets - Starting Code
This repository contains the starting code for a web application called Secrets. Secrets is a platform where users can anonymously share their secrets with others. The application utilizes technologies such as Node.js, Express.js, MongoDB, and Passport.js for authentication.

Features
User Registration: Users can create an account by providing a username and password.
User Login: Existing users can log in using their credentials.
Google and Facebook Authentication: Users can also authenticate using their Google or Facebook accounts.
Submit Secrets: Authenticated users can submit their secrets anonymously.
View Secrets: Users can view secrets shared by other users.
Logout: Users can securely log out of their accounts.
Setup Instructions
To run the application locally, follow these steps:

Clone the repository to your local machine using git clone.
Install the required dependencies by running npm install.
Set up environment variables:
Create a .env file in the root directory of the project.
Add the following variables to the .env file:
GOOGLE_CLIENT_ID: Your Google OAuth client ID.
GOOGLE_CLIENT_SECRET: Your Google OAuth client secret.
FACEBOOK_APP_ID: Your Facebook app ID.
FACEBOOK_APP_SECRET: Your Facebook app secret.
SESSION_SECRET: A secret key for session encryption.
Make sure you have MongoDB installed and running locally.
Update the MongoDB connection URL in the mongoose.connect() function call in app.js if necessary.
Start the application by running npm start or node app.js.
Access the application in your web browser at http://localhost:3000.
Feel free to modify the code and customize the application according to your requirements.

Please note that this is the starting code, and you may need to add additional functionality or make modifications as per your project's needs.

For more information, please refer to the project's documentation and comments in the code.

Enjoy using Secrets - Starting Code!
