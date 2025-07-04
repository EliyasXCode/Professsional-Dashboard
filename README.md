# Personal Dashboard - VS Code Setup Guide

## Method 1: Using Live Server Extension (Recommended)

1. **Install Live Server Extension:**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Live Server" by Ritwick Dey
   - Click Install

2. **Run the Project:**
   - Open the project folder in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - Your browser will automatically open with the dashboard

## Method 2: Using VS Code's Built-in Server

1. **Install Live Preview Extension:**
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Live Preview" by Microsoft
   - Click Install

2. **Run the Project:**
   - Open `index.html`
   - Press Ctrl+Shift+P (Command Palette)
   - Type "Live Preview: Start Server"
   - Select it and your project will open in a preview panel

## Method 3: Manual Browser Opening

1. **Simple File Opening:**
   - Navigate to your project folder
   - Double-click `index.html`
   - It will open in your default browser

## Project Structure
```
personal-dashboard/
├── index.html          # Main HTML file
├── src/
│   ├── style.css      # All styles and themes
│   └── main.js        # Dashboard functionality
└── README.md          # This file
```

## Features
- ✅ Real-time clock with greeting
- ✅ Weather display (demo data)
- ✅ Todo list with local storage
- ✅ Quick notes manager
- ✅ Bookmark/links organizer
- ✅ Daily habit tracker
- ✅ Dark/Light theme toggle
- ✅ Keyboard shortcuts (Ctrl+K, Ctrl+J, Ctrl+L)
- ✅ Responsive design

## Keyboard Shortcuts
- `Ctrl/Cmd + K` - Add new task
- `Ctrl/Cmd + J` - Add new note
- `Ctrl/Cmd + L` - Add new link
- `Escape` - Close any open modal

## Browser Compatibility
Works in all modern browsers (Chrome, Firefox, Safari, Edge)
No additional dependencies or build process required!