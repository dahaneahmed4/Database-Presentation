# 🗄️ Database Master Presentation

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

> A high-fidelity, interactive presentation engine built entirely in a **single HTML file**. No PowerPoint, no Keynote, no dependencies.

## 📖 Overview

This project is a standalone web application designed to present **Database Concepts and Relational Models**. It replaces traditional slide software with a lightweight, code-driven approach.

The presentation features a "Cyberpunk/Enterprise" aesthetic, complete with a matrix-style digital rain background, CSS-only diagramming, and smooth 3D transitions.

### ✨ Key Features

* **⚡ Zero Dependencies:** Runs in any modern browser (Chrome, Firefox, Safari, Edge).
* **📂 Single File Portability:** Everything (HTML, CSS, JS) is contained in `database_presentation.html`.
* **🎨 Canvas Animation:** Custom-written HTML5 Canvas "Digital Rain" background effect.
* **🧩 CSS Visualizations:** Includes a responsive Entity Relationship Diagram (ERD) drawn purely with CSS (no images).
* **⌨️ Keyboard Support:** Full navigation support using Arrow Keys and Spacebar.
* **📱 Responsive:** Adapts to various screen sizes (Laptops, Desktops, Tablets).

---

## 🚀 Quick Start

You do not need to install Node.js, Python, or any servers.

1.  **Clone the repository** (or download the ZIP):
    ```bash
    git clone [https://github.com/YOUR_USERNAME/database-presentation.git](https://github.com/YOUR_USERNAME/database-presentation.git)
    ```
2.  **Locate the file:**
    Find `database_presentation.html` in the folder.
3.  **Run:**
    Double-click the file to open it in your default web browser.

---

## 🎮 Controls

| Key | Action |
| :--- | :--- |
| `→` (Right Arrow) | Next Slide |
| `←` (Left Arrow) | Previous Slide |
| `Spacebar` | Next Slide |
| `Click (UI)` | Use the on-screen Next/Prev buttons |

---

## 🛠️ Customization

Because this is a single-file application, it is incredibly easy to modify. Open `database_presentation.html` in any text editor (VS Code, Sublime Text, Notepad++).

### Changing Content
Scroll to the HTML section (approx line 330). You will see slide containers:
```html
<div class="slide" id="slide-1">
   <h2>Your Title Here</h2>
   <p>Your content here...</p>
</div>
