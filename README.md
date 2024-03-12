## User Signup and Profile Display with React and Vite

This project implements a user signup form with validation and displays user profiles on a separate page. It's built with React and Vite for a fast development experience.

### Getting Started

**Prerequisites:** Node.js and npm (or yarn) installed on your system. You can download them from [https://nodejs.org/en](https://nodejs.org/en)

**Clone the Repository:**

git clone [https://github.com/H-erbie/vibtree.git](https://github.com/H-erbie/vibtree.git)

cd user-signup-profile

**Install Dependencies:**
npm install

**Running the Application**

    Start the development server:

    npm run dev


    This will open the application in your default browser at http://localhost:3000/

**Testing and Development:**
        The application runs in hot-reload mode. Changes to your React components will be reflected in the browser automatically.
        Use the signup form to create new users with valid information.
        The profile page should display the saved user details.

**Built-in Features**

    Real-time validation for signup form fields (name, mobile number, DOB, email, password).
    Responsive layout that adapts to different screen sizes.
    User profiles displayed in a grid layout with basic information and placeholder images
    Edit and delete functionalities for user profiles.
    Profile picture upload option.

**Code Structure**

The project uses a basic React component structure. Main components include:

    SignupForm.jsx: Handles user signup with validation and data storage.
    UserProfile.jsx: Displays individual user profile information.
    App.jsx: Main application component that renders the signup form and profile page.

**Deployment**

For production deployment, you can build the project for optimal performance:
Bash

npm run build


The built files will be placed in the dist folder. You can serve these files from a web server.
Contribution

Feel free to fork this repository and make improvements! You can add features like edit/delete profiles or explore using a state management library like Redux for complex data handling.

This README provides a basic guide to running the application locally. Feel free to explore the codebase and customize it further to showcase your skills!


 

