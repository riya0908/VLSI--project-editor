# VLSI--project-editor
VLSI Project Editor is a lightweight, customizable tool designed to streamline the development and management of VLSI design projects. It supports modular editing, hierarchical design visualization, and integration with simulation workflows, making it ideal for students, researchers, and engineers working in digital design and chip architecture.

VLSI Project Editor
The VLSI Project Editor is a simple, single-page web application designed to help students and enthusiasts manage and write their Verilog projects. The application provides a user-friendly interface for creating, editing, saving, and deleting Verilog code snippets, with all data securely stored in a private Firebase Firestore database.

Features
Project Management: Easily create new projects and save your work with a unique project name.

Verilog Code Editor: A dedicated editor area with a monospaced font for writing your Verilog code.

Real-time Storage: All projects are automatically saved to a private Firestore collection tied to your user ID, allowing you to access your work from any device.

User ID Display: Your unique user ID is displayed on the page to help you identify your private data.

Responsive Design: The application is built with a responsive layout to work well on both desktop and mobile devices.

How to Use
Start a New Project: Click the "New Project" button to clear the editor and begin a new design.

Name and Code: Enter a descriptive name for your project in the input field and write your Verilog code in the editor area.

Save Your Work: Click the "Save Project" button to securely store your project in the database. If it's a new project, it will be added to your list; if you're editing an existing one, the changes will be saved.

Load a Project: Select a project from the list on the left to load its name and code into the editor.

Delete a Project: If you're on a loaded project, click the "Delete Project" button to remove it. A confirmation dialog will appear to prevent accidental deletion.

Technologies Used
HTML5: For the core structure of the web page.

Tailwind CSS: A utility-first CSS framework used for styling and creating the responsive layout.

Firebase Firestore: A NoSQL cloud database used for persistent and real-time storage of user projects.

Firebase Authentication: Used to securely identify and authenticate users, ensuring each user's projects are kept private.

Future Enhancements
Syntax highlighting for Verilog code.

Integration with an online Verilog simulator.

Collaboration features to allow multiple users to work on the same project.

The ability to export project code as a .v file.
