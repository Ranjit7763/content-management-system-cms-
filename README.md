

### Front-End:
1. **Signup Page (index.html)**:
   - A user interface for signing up to the system. It includes HTML and CSS, and a form for collecting user information such as name, mobile number, email, and password.
   
2. **Login Page (login.html)**:
   - A user interface for logging into the system. It includes form fields for a username, password, and a captcha for security. JavaScript is used for captcha generation and validation.

3. **CMS Page (cms.html)**:
   - The main interface for managing contacts. It includes a form to add, edit, search, and delete contacts. It also allows for updating a contact list. LocalStorage is used to store contacts temporarily on the client side.

### Back-End:
1. **App.js (Server-side code)**
   - An Express.js application connecting to a MongoDB database.
   - Includes routes for signing up, logging in, and adding contacts.
   - It uses Mongoose for data modeling and interacting with MongoDB. There are two models: one for users and another for contacts.


