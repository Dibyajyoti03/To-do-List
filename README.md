# ✨ Todo List App

A beautiful, responsive todo list application with a glassmorphism design that helps you stay organized and productive.

![Todo List Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## 🌟 Features

### ✅ Core Functionality

- **Add Tasks** - Quickly add new tasks with Enter key or click
- **Mark Complete** - Check off completed tasks with visual feedback
- **Delete Tasks** - Remove individual tasks or clear all at once
- **Persistent Storage** - Your tasks are saved locally and persist between sessions

### 🎛️ Smart Filtering

- **View All** - See your complete task list
- **Completed Tasks** - Focus on what you've accomplished
- **Pending Tasks** - See what still needs attention
- **Toggle Filters** - Click again to remove active filters

### 🎨 Beautiful Design

- **Glassmorphism UI** - Modern translucent design with backdrop blur
- **Responsive Layout** - Works perfectly on desktop and mobile
- **Smooth Animations** - Subtle transitions and hover effects
- **Custom Scrollbar** - Elegant scrolling experience
- **Empty State** - Clean placeholder when no tasks exist

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
   ```

2. **Add required assets**
   Make sure you have these files in your project directory:

   - `background.jpg` - Background image
   - `empty.svg` - Empty state illustration
   - `check.svg` - Checkmark icon

3. **Launch the app**
   Simply open `index.html` in your web browser or use a local server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .

   # Using PHP
   php -S localhost:8000
   ```

4. **Start organizing!** 🎉

## 📱 How to Use

### Adding Tasks

- Type your task in the input field
- Press **Enter** or click the **➕** button
- Your task appears at the top of the list

### Managing Tasks

- **Complete**: Click the circle next to any task
- **Delete**: Click the **✕** button on individual tasks
- **Filter**: Use "Complete" and "Incomplete" buttons to filter views
- **Clear All**: Use "Delete All" to remove all tasks

### Keyboard Shortcuts

- **Enter** - Add new task
- **Click** - Toggle task completion

## 🛠️ Technical Details

### Built With

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with glassmorphism effects
- **Vanilla JavaScript** - No frameworks, pure JS functionality
- **Font Awesome 4.5.0** - Icon library
- **Local Storage API** - Persistent data storage

### File Structure

```
todo-list-app/
│
├── index.html          # Main HTML structure
├── style.css           # Styling and animations
├── script.js           # Application logic
├── background.jpg      # Background image
├── empty.svg          # Empty state icon
├── check.svg          # Checkmark icon
└── README.md          # This file
```

### Key Features Implementation

- **Responsive Design**: Flexbox layout with mobile-first approach
- **Data Persistence**: LocalStorage for cross-session data retention
- **Dynamic Filtering**: Real-time task filtering without page refresh
- **Accessibility**: Proper labeling and keyboard navigation support

## 🎨 Customization

### Colors & Themes

The app uses a purple glassmorphism theme. To customize:

```css
/* Main accent color */
border: 2px solid #e6b7eca1; /* Purple accent */

/* Background blur container */
backdrop-filter: blur(15px); /* Glassmorphism effect */

/* Task items */
background-color: #463c7b; /* Task background */
```

### Styling Variables

Consider adding CSS custom properties for easier theming:

```css
:root {
  --primary-color: #e6b7eca1;
  --task-bg: #463c7b;
  --text-color: #eee;
  --border-radius: 10px;
}
```

## 🔧 Browser Support

| Browser | Version | Support |
| ------- | ------- | ------- |
| Chrome  | 60+     | ✅ Full |
| Firefox | 55+     | ✅ Full |
| Safari  | 12+     | ✅ Full |
| Edge    | 79+     | ✅ Full |

_Note: Glassmorphism effects require modern browser support for `backdrop-filter`_

## 📈 Performance

- **Lightweight**: No external frameworks or heavy dependencies
- **Fast Loading**: Minimal asset footprint
- **Smooth Interactions**: Hardware-accelerated CSS transitions
- **Efficient Storage**: Optimized localStorage usage

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions

- [ ] Dark/Light theme toggle
- [ ] Task categories and tags
- [ ] Due dates and reminders
- [ ] Export/Import functionality

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for the Roboto font family
- **CSS Glassmorphism** design inspiration from modern UI trends

---

<div align="center">

**Made with ❤️ for productivity enthusiasts**

[⭐ Star this repo](https://github.com/Dibyajyoti03/todo-list-app) | [🐛 Report Bug](https://github.com/Dibyajyoti03/todo-list-app/issues) | [💡 Request Feature](https://github.com/Dibyajyoti03/todo-list-app/issues)

</div>

---

> 💡 **Pro Tip**: Keep your tasks specific and actionable for maximum productivity!

---

## 👨‍💻 Author

**Dibyajyoti Mohanty**  
📧 Email: dibyajyotimty508@gmail.com  
GitHub: [@Dibyajyoti03](https://github.com/Dibyajyoti03)

---
