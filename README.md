# Task Tracker

A dynamic and aesthetic To-Do List web application for managing your daily tasks efficiently.

## Features

- ✅ **Add Tasks** - Easily add new tasks to your to-do list
- ✅ **Mark Complete** - Check off completed tasks with a single click
- ✅ **Delete Tasks** - Remove tasks you no longer need
- 🎨 **Theme Switching** - Choose between three beautiful themes:
  - Standard Theme
  - Light Theme
  - Darker Theme
- 💾 **Local Storage** - Tasks are saved locally in your browser, so they persist even after you close the page
- 🕐 **Date & Time Display** - View the current date and time

## Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and theme management
- **JavaScript** - Interactive functionality and local storage
- **Font Awesome** - Icons for check and delete buttons
- **Google Fonts** - Work Sans font family

## Project Structure

```
Task-Tracker/
├── index.html          # Main HTML file
├── CSS/
│   ├── main.css        # Main styles
│   └── corner.css      # Corner styling
├── JS/
│   ├── main.js         # Core functionality
│   └── time.js         # Date and time display
├── assets/
│   └── favicon.png     # Website favicon
└── README.md           # This file
```

## How to Use

1. Open `index.html` in your web browser
2. Type your task in the input field
3. Click "I Got This!" button to add the task
4. Click the **check button** (✓) to mark a task as complete
5. Click the **trash button** (🗑) to delete a task
6. Switch themes using the color circles at the top

## Theme Selection

- **Standard Theme** (Default) - Classic dark theme
- **Light Theme** - Clean and bright interface
- **Darker Theme** - Extra dark mode for low-light environments

Your selected theme is saved automatically!

## Local Storage

All your tasks are stored in your browser's local storage. This means:
- Tasks persist after closing the browser
- Tasks are specific to this browser/device
- Clearing browser data will remove your tasks

## Features Explained

### Add Task
- Enter task text in the input field
- Click "I Got This!" button or press Enter
- Task appears in the list below

### Complete Task
- Click the green checkmark button next to a task
- Task text will be struck through to indicate completion
- Click again to uncomplete the task

### Delete Task
- Click the red trash button next to a task
- Task will animate downward before disappearing
- Deleted tasks are removed from local storage

### Date & Time
- Current date and time display in the top left corner
- Updates when the page loads

## Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Installation

No installation required! Simply clone or download the repository and open `index.html` in your browser.

```bash
git clone https://github.com/siddhantsupe13/Task-Tracker.git
cd Task-Tracker
# Open index.html in your browser
```

## Future Enhancements

- Due dates for tasks
- Task categories
- Priority levels
- Export/Import tasks
- Cloud synchronization
- Mobile app version

## License

This project is open source and available under the MIT License.

## Author

**Siddhant Supe**

## Feedback

If you have any suggestions or feedback, feel free to open an issue or contact me!

---

**Made with ❤️ by Siddhant Supe**
