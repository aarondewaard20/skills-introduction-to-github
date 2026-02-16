# To-Do List Web Application

A beautiful, fully-functional to-do list application built with vanilla HTML, CSS, and JavaScript. This app helps you stay organized and productive with a clean, modern interface.

## ✨ Features

- ✅ Add new tasks quickly
- ✏️ Mark tasks as complete/incomplete
- 🗑️ Delete individual tasks
- 🔍 Filter tasks (All, Active, Completed)
- 📊 Task counter showing active tasks
- 🧹 Clear all completed tasks at once
- 💾 Automatic data persistence using LocalStorage
- 📱 Fully responsive design for mobile and desktop
- 🎨 Beautiful gradient UI with smooth animations

## 🚀 Getting Started

### Prerequisites

No dependencies required! This is a pure HTML/CSS/JavaScript application that runs in any modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/aarondewaard20/skills-introduction-to-github.git
cd skills-introduction-to-github/app
```

2. Open the application:
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Navigate to `http://localhost:8000` (if using a local server)

## 📖 How to Use

1. **Add a Task**: Type your task in the input field and click "Add Task" or press Enter
2. **Complete a Task**: Click the checkbox next to a task to mark it as complete
3. **Delete a Task**: Hover over a task and click the "Delete" button
4. **Filter Tasks**: Use the filter buttons to view All, Active, or Completed tasks
5. **Clear Completed**: Click "Clear Completed" to remove all finished tasks

## 🏗️ Project Structure

```
app/
├── index.html          # Main HTML structure
├── css/
│   └── styles.css      # All styling and animations
└── js/
    └── app.js          # Application logic and functionality
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with Flexbox, animations, and gradients
- **JavaScript (ES6+)**: Object-oriented programming with classes
- **LocalStorage API**: For data persistence

## 💡 Key Features Explained

### Data Persistence
The app uses the browser's LocalStorage to save your tasks, so they persist even after closing the browser.

### Object-Oriented Design
The application is built using a `TodoApp` class that manages state and handles all user interactions.

### Responsive Design
The interface adapts seamlessly to different screen sizes, providing an optimal experience on both desktop and mobile devices.

## 🎨 Customization

You can easily customize the app's appearance by modifying the CSS variables and styles in `css/styles.css`:

- Change colors in the gradient background
- Modify button styles and animations
- Adjust spacing and sizing
- Update fonts and typography

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.

## 🙏 Acknowledgments

- Built as part of the GitHub Skills learning path
- Inspired by modern task management applications
- Design patterns from best practices in web development

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

Made with ❤️ using HTML, CSS, and JavaScript
