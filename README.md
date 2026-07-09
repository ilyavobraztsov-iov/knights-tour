# To-Do List Application

A simple and elegant to-do list application with local storage functionality built with vanilla HTML, CSS, and JavaScript.

## Features

✅ **Add Tasks** - Easily add new tasks to your to-do list
✅ **Mark Complete** - Check off tasks when completed
✅ **Delete Tasks** - Remove individual tasks
✅ **Filter Tasks** - View all, active, or completed tasks
✅ **Local Storage** - Your tasks are automatically saved in browser storage
✅ **Statistics** - See total and completed task counts
✅ **Responsive Design** - Works great on desktop and mobile devices
✅ **Beautiful UI** - Modern gradient design with smooth animations

## How to Use

1. **Open the Application** - Open `index.html` in your web browser
2. **Add a Task** - Type in the input field and click "Add" or press Enter
3. **Mark Complete** - Click the checkbox next to a task to mark it as complete
4. **Delete a Task** - Click the "Delete" button to remove a task
5. **Filter Tasks** - Use the filter buttons to view all, active, or completed tasks
6. **Clear Completed** - Click "Clear Completed" to remove all finished tasks

## How Local Storage Works

- Tasks are automatically saved to your browser's local storage
- Your to-do list persists even after closing and reopening the browser
- No server or internet connection required
- Data is stored locally on your device

## Files

- `index.html` - HTML structure of the application
- `styles.css` - Styling and responsive design
- `script.js` - JavaScript logic and local storage functionality
- `README.md` - This file

## Browser Compatibility

Works on all modern browsers that support:
- HTML5
- CSS3
- JavaScript ES6
- Local Storage API

## Technical Details

- **Storage Method**: Browser Local Storage (localStorage API)
- **Framework**: Vanilla JavaScript (no dependencies)
- **Architecture**: Object-Oriented Programming with a TodoApp class
- **Data Structure**: Array of task objects with id, text, completed status, and timestamp

## Tips

- Hover over task text to see when it was created
- Tasks are automatically saved - no need to manually save
- Maximum characters per task is unlimited
- The app works offline
