# Notes_Using_JavaScript.github.io THANKS FOR SUPPORT

Notes Application
This is a simple web-based application that allows users to create, edit, and delete notes. The application uses localStorage to save notes so they persist even after the browser is refreshed.

Features
Create Notes: Add a new note by clicking the "Create Notes" button.
Edit Notes: Click inside a note to edit its content.
Delete Notes: Click the delete icon inside a note to remove it.
Persistent Storage: Notes are saved automatically in your browser’s local storage and will remain even after you refresh or close the page.
File Structure
bash
Copy code
/project-directory
│
├── index.html       # The main HTML file
├── style.css        # The styling for the app
├── script.js        # JavaScript logic for functionality
├── /images          # Folder containing image assets
│   ├── notes.png    # Icon for the header
│   ├── edit.png     # Icon for the "Create Notes" button
│   ├── delete.png   # Icon for deleting notes
How to Run
Download or Clone the Repository:

bash
Copy code
git clone https://github.com/your-repo/notes-app.git
Navigate to the Project Directory:

bash
Copy code
cd notes-app
Open the Application: Open the index.html file in your browser to run the application.

How It Works
When the page loads, it retrieves previously saved notes from localStorage and displays them.
Clicking the "Create Notes" button adds a new editable note with a delete icon.
Any changes you make to the notes are saved automatically in real-time.
Clicking the delete icon removes the note and updates the storage.
Requirements
A modern browser (e.g., Chrome, Firefox, Edge).
Internet connection (only needed for downloading the project).
Customization
Styles: Modify style.css to change the appearance.
Icons: Replace the images in the /images folder to use your own icons.
Functionality: Extend script.js to add features like note colors, search functionality, or note categories.
Known Issues
Pressing "Enter" while editing a note inserts a line break instead of creating a new note. This is intentional to keep the notes compact.
Notes are stored in the browser’s localStorage, which has a size limit.

 
