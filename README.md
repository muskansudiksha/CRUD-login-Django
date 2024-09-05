# CRUD-login-Django

Objective:
The project aims to build a web application where users can perform Create, Read, Update, and Delete (CRUD) operations on employee records, with additional authentication features to ensure only authorized users can manage the data.

Key Features:

User Authentication:
User login and registration functionality.
Access control: Only authenticated users can add, edit, or delete employees.
Logout feature to securely end user sessions.

Employee Management:
Create: Users can add new employee records, including personal information like name, contact, role, and profile picture.
Read: List of all employees displayed on the homepage with pagination.
Update: Edit employee details through a form modal with data preloaded for existing employees.
Delete: Soft deletion (deactivation) of employees, keeping their data in the database but excluding them from the list.

Form Validation:
Frontend validation (using JavaScript) for checking input fields in real-time.
Server-side validation using Django forms and models to ensure data integrity.

File Uploads:
Profile picture upload for employees with the ability to clear or update the image.

UI and Bootstrap Modals:
Dynamic Bootstrap modals for creating and editing employee data.
Responsive UI using Bootstrap for user-friendly interactions.

Technologies Used:
Django (backend framework)
Bootstrap (UI/Frontend framework)
JavaScript (for frontend validation and dynamic modals)
SQLite (database for storing employee data)
Pillow (for handling image uploads)

The project ensures smooth user experience through well-integrated authentication and validation mechanisms, while providing a secure and intuitive platform for managing employee records.
