# React Task Management Application Documentation

github repo   - https://github.com/Shefali889/taskManagementReact
Hosted url - https://task-management-shefali.vercel.app

### How to Start ?
> `npm install`

> `npm start`

### How to Build ?
> `npm run build`

Builds the app for production to the `build` folder.


## 1.  Project Structure
### Source Directory (src)
Assets (assets)
TodoLogo.png: Logo image for the application.
someOtherImage.png: Another image asset.
colorCodes.js: File containing an array of color codes used in the application.

### Components (components)
LoginSignup.js: Component handling user authentication (login and signup).

Main.js: Main dashboard component for managing tasks.

Task.js: Component representing a single task with functionalities for editing, deleting, and marking tasks as complete or incomplete.

TaskForm.js: Form component for adding and editing tasks.

### Other Files 

App.js: Main component managing the application's state and rendering other components based on user actions.

index.js: Entry point of the React application.

index.css: CSS file for styling the application.

reportWebVitals.js: File for measuring and reporting performance metrics of the application.



## 2. Components Overview
index.js - The entry point of the React application.

App.js - The main component that manages the logged-in state and renders either the Main or LoginSignup component based on the user's login status.

components/LoginSignup.js - Handles user authentication, allowing users to log in or sign up.

components/Main.js - The main dashboard where users can view, filter, add, edit, and delete tasks.

components/Task.js - Represents a single task with functionalities to edit, delete, and mark tasks as complete or incomplete.

components/TaskForm.js - A form component for adding and editing tasks.



## 3. Additional Information

### i) Local Storage
Users: The user information (username and password) is stored in localStorage under the key allusers.

Current User: The currently logged-in user's username is stored under the key username.

Tasks: The list of tasks is stored under the key tasks.

### ii) Features
Authentication: Users can log in or sign up. Authentication is simple and handled via localStorage.

Task Management: Users can add, edit, delete, and mark tasks as complete or incomplete.

Filtering: Tasks can be filtered based on their status (All, Completed, Active).

Modal: A modal is used for adding and editing tasks.