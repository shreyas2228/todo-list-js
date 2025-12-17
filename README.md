# To-Do List with LocalStorage

A simple and elegant dark-themed to-do list application that persists your tasks using browser's LocalStorage.

## Features

- ✅ Add new tasks
- ✅ Mark tasks as completed/uncompleted by clicking on them
- ✅ Delete tasks
- ✅ Data persistence using LocalStorage (tasks remain after page refresh)
- ✅ Clean, dark mode UI
- ✅ Responsive design

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with dark theme
- **JavaScript (ES6+)** - Functionality and LocalStorage integration

## How to Use

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Add a task** by typing in the input field and clicking "Add Task"
4. **Mark as complete** by clicking on a task
5. **Delete a task** by clicking the "Delete" button

## Project Structure

```
01_todo-localstorage/
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── script.js       # JavaScript logic
└── README.md       # Project documentation
```

## Key Functionality

### LocalStorage Integration
- Tasks are automatically saved to browser's LocalStorage
- Data persists across browser sessions
- Tasks are loaded when the page is refreshed

### Task Management
- Each task has a unique ID (timestamp-based)
- Tasks can be toggled between completed/uncompleted states
- Tasks can be deleted individually

## Installation

No installation required! Simply open the `index.html` file in any modern web browser.

```bash
# Clone the repository (if using git)
git clone [your-repo-url]

# Navigate to the project folder
cd 01_todo-localstorage

# Open index.html in your browser
```

## Browser Compatibility

Works on all modern browsers that support:
- LocalStorage API
- ES6 JavaScript
- CSS3

## Future Enhancements

- [ ] Edit existing tasks
- [ ] Filter tasks (All, Active, Completed)
- [ ] Clear all completed tasks
- [ ] Task priorities
- [ ] Due dates
- [ ] Categories/Tags

## License

This project is open source and available for educational purposes.

## Author

Created as part of a JavaScript projects learning series.
