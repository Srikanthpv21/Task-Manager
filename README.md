# Task-Manager
Task Manager
# ✨ Task Manager

A beautiful, responsive task management application built with vanilla HTML, CSS, and JavaScript. Features a modern glassmorphism design with smooth animations and intuitive user experience.

## 🌟 Features

- **Add Tasks**: Create new tasks with customizable priority levels
- **Priority System**: Organize tasks by High, Medium, or Low priority
- **Task Filtering**: Filter tasks by status (All, Pending, Completed) or priority
- **Task Statistics**: Real-time overview of total, pending, and completed tasks
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Glassmorphism design with smooth animations and transitions
- **Keyboard Support**: Press Enter to quickly add tasks
- **Task Management**: Mark tasks as complete, delete unwanted tasks
- **Time Tracking**: Shows when tasks were created with relative timestamps

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required

### Installation

1. Download the HTML file to your local machine
2. Open the file in any web browser
3. Start managing your tasks immediately!

### Usage

1. **Adding Tasks**:
   - Type your task in the input field
   - Select priority level (Low, Medium, High)
   - Click "Add Task" or press Enter

2. **Managing Tasks**:
   - Check the checkbox to mark tasks as complete
   - Click the delete button (🗑️) to remove tasks
   - Use filter buttons to view specific task categories

3. **Filtering**:
   - **All Tasks**: View all tasks regardless of status
   - **Pending**: Show only incomplete tasks
   - **Completed**: Show only finished tasks
   - **High Priority**: Show only high-priority tasks

## 🎨 Design Features

- **Gradient Background**: Beautiful purple gradient backdrop
- **Glassmorphism Effect**: Semi-transparent containers with backdrop blur
- **Smooth Animations**: Slide-in effects for new tasks and hover animations
- **Color-Coded Priorities**: Visual distinction between priority levels
- **Responsive Layout**: Adapts to different screen sizes automatically

## 📱 Browser Compatibility

- ✅ Chrome 88+
- ✅ Firefox 84+
- ✅ Safari 14+
- ✅ Edge 88+

## 🔧 Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, and animations
- **Vanilla JavaScript**: ES6+ features and class-based architecture

### Key Technologies Used
- CSS Grid & Flexbox for layout
- CSS Custom Properties for theming
- CSS Animations and Transitions
- Local DOM manipulation
- Event delegation for dynamic content

### File Structure
```
task-manager/
│
├── index.html          # Main application file
└── README.md          # This file
```

## 💡 Features Explained

### Priority System
- **High Priority**: Red badge, urgent tasks
- **Medium Priority**: Orange badge, standard tasks  
- **Low Priority**: Green badge, non-urgent tasks

### Statistics Dashboard
Real-time counters showing:
- Total number of tasks
- Pending (incomplete) tasks
- Completed tasks

### Data Persistence
Currently stores data in memory for the session. For permanent storage, you can extend the `saveTasks()` and `loadTasks()` methods to use:
- localStorage for browser-based persistence
- A backend API for cloud storage
- IndexedDB for larger datasets

## 🛠️ Customization

### Changing Colors
Edit the CSS custom properties in the `<style>` section:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --accent-color: #667eea;
  /* Add more custom properties */
}
```

### Adding New Priority Levels
1. Update the `<select>` options in HTML
2. Add corresponding CSS classes for styling
3. Update the filtering logic in JavaScript

### Extending Functionality
The modular JavaScript class structure makes it easy to add:
- Due dates
- Task categories
- Subtasks
- Task notes
- Export functionality

## 🤝 Contributing

This is a standalone project, but feel free to:
- Report bugs or suggest improvements
- Fork and modify for your own use
- Share enhancements with the community

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🎯 Future Enhancements

Potential features for future versions:
- [ ] Data persistence with localStorage
- [ ] Task due dates and reminders
- [ ] Drag and drop task reordering
- [ ] Task categories and tags
- [ ] Dark/light theme toggle
- [ ] Task search functionality
- [ ] Export tasks to CSV/JSON
- [ ] Task notes and descriptions
- [ ] Subtask support
- [ ] Keyboard shortcuts

---

**Enjoy organizing your tasks with style! ✨**
