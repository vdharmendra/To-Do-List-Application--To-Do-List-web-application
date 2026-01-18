# To-Do List Web Application

A simple, clean, and minimalist To-Do List web app built with Node.js, Express, EJS, and Bootstrap 5. This app allows users to manage daily tasks and work-related tasks separately.

- 
👨‍💻 Author
Virendra D. Verma
<a href="https://www.linkedin.com/in/dharmendraverma95/" target="_blank">🧑‍💻 LinkedIn Profile </a> | <a href="https://www.behance.net/dhirukumar" target="_blank">🧑‍💻 Behance Profile </a>

## 🌐 Live

Visit our live link: (https://to-do-list-application-to-do-list-web.onrender.com/)

-


### Features

- View daily tasks with the current date as the list title.
- Separate Work task list accessible via /work route.
- Add new tasks to either the default list or work list.
- Responsive layout styled with Bootstrap 5.
- Interactive checkboxes to mark tasks as completed (with line-through styling).
- Clean UI with custom CSS for additional styling.


### Technologies Used

- Node.js
- Express.js
- EJS Templating Engine
- Body-parser for handling POST requests
- Bootstrap 5 for styling and responsiveness
- Custom CSS for UI enhancements

### Project Structure
.
├── app.js               # Main server file
├── views
│   └── lists.ejs        # EJS template for task lists
├── public
│   └── css
│       └── style.css    # Custom stylesheet
└── README.md            # Project documentation

### Usage

- On the home page (/), you will see the daily tasks list titled with the current day and date.
- Navigate to /work to view and manage your work tasks.
- Use the input box and "Add" button to add new tasks to the current list.
- Mark tasks as completed by clicking the checkbox (visual line-through effect).
- The application does not currently persist tasks to a database; tasks reset when the server restarts.

### Notes

- The app uses server-side rendering with EJS.
- Tasks are stored in memory in two arrays: items (default tasks) and workList (work tasks).
- The checkboxes toggle task completion styling only on the client side (no persistence).