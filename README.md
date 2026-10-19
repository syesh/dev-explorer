# DevExplorer 🚀

A lightweight web application built as part of a hands-on web development workshop conducted for 2nd-year students.

---

## 📖 About the Project

**DevExplorer** is a simple, interactive resource directory designed to teach students foundational frontend development without external libraries or frameworks. It demonstrates how HTML, CSS, and modern vanilla JavaScript work together to build a responsive, functional user interface with live search and category filtering.

---

## 🎯 Workshop Learning Objectives

This project was built to help 2nd-year students understand core web development concepts:

### 1. HTML5 Structure & Semantics
- Using semantic elements (`<header>`, `<main>`, `<button>`, `<input>`).
- Utilizing custom `data-*` attributes (`data-cat`) to store metadata in HTML elements.

### 2. CSS Styling & Layouts
- Structuring components using **Flexbox** layout.
- Styling reusable UI patterns: Cards, badges, and responsive action buttons.
- State-based styling (e.g., active filter buttons).

### 3. Modern JavaScript (ES6+) & DOM Manipulation
- Selecting DOM elements using `querySelector` and `querySelectorAll`.
- Handling user events (`input` for instant search, `click` for category switching).
- Dynamic rendering using template literals and string interpolation.
- Essential JavaScript Array methods:
  - `.map()` for generating HTML strings from an array of objects.
  - `.filter()` for querying items based on search terms or categories.
  - `.includes()` for case-insensitive string matching.

---

## 📁 Project Structure

```text
wokrshop-ct/
├── index.html    # Core markup, header, search input, and filter controls
├── style.css     # Clean styles, button interactions, and card grid layout
└── script.js     # Data store, DOM event listeners, and filtering logic
```

---

## 🚀 Getting Started

No build tools, bundlers, or package installations are required!

### Option 1: Open Directly
Simply open `index.html` in any modern web browser.

### Option 2: Using a Local Development Server
For a better development experience (e.g. live reload):

- **VS Code**: Install the **Live Server** extension and click **"Go Live"**.
- **Node.js**:
  ```bash
  npx serve .
  ```
- **Python 3**:
  ```bash
  python3 -m http.server 8000
  ```
  Then visit `http://localhost:8000` in your browser.
