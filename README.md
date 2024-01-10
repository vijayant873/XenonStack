# XenonStack--User Authentication Web App

This repository contains a user authentication web application developed using HTML, CSS, JavaScript for the frontend, and Node.js, Express, and Mongoose for the backend.

## Features

- **Sign In Page:** Existing users can sign in using their credentials.
- **Sign Up Page:** New users can create an account by providing necessary information and then they are redirected to Sign In page to Sign In.
- **Contact Us Page:** Users can submit inquiries or messages to the admin.
- **Home Page:** Accessible only after successful authentication.

## Technologies Used

- **Frontend:**
  - HTML
  - CSS
  - JavaScript

- **Backend:**
  - Node.js
  - Express.js
  - Mongoose (MongoDB)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/user-authentication-web-app.git
   
2. **Install dependencies:**

   cd user-authentication-web-app
   npm install
   
3. **Set up environment variables:**

    Create a .env file in the root directory and add necessary variables 
    (e.g., database connection URI, session secret).

4. **Run the application:**
   
    npm start

5. **Access the application:**

    Open your web browser and go to http://localhost:3000 to use the 
    application.

## Usage

1. Go to the Sign Up page to create a new user account.
2. Sign in using your credentials on the Sign In page.
3. Use the Contact Us page to send messages or inquiries.
4. Access the Home Page after successful authentication.
   
## Folder Structure

1. /public: Contains static assets (CSS, client-side JavaScript, images).
2. /views: Includes HTML templates for different pages.
3. /routes: Defines routes for various functionalities.
4. /models: Contains Mongoose models for the database schema.
