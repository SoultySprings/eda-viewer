# 📓 SoultySprings Notebook Viewer

An **interactive Jupyter Notebook (`.ipynb`) viewer** built with **pure HTML, CSS, and JavaScript** — no backend or heavy frameworks required.  
It fetches raw notebooks directly from GitHub, parses the JSON, and dynamically renders **markdown, code cells, and outputs** (plots, tables, images, etc.) in a clean neomorphic design with a **persistent dark/light theme**.

---

## ✨ Features
- 📂 **Sidebar Notebook Selector** – Click to open and toggle between `.ipynb` files.
- 🖋️ **Markdown Rendering** – Uses [Marked.js](https://github.com/markedjs/marked) for smooth Markdown support.
- 💻 **Code Cell Display** – Renders Python code cells in a styled block.
- 📊 **Output Rendering**:
  - Text, stdout, and errors
  - Inline tables (with horizontal scrolling for large tables)
  - Images (`png`, `jpeg`, `svg`)
  - HTML/iframes (e.g., interactive Plotly charts)
- 🎨 **Neomorphic Design** with shadows, gradients, and glassmorphism.
- 🌗 **Dark / Light Mode** toggle with a smooth circular wipe transition and persistent theme memory (via `localStorage`).
- 🧭 **Welcome Screen** with fun quotes (philosophy + science facts + hidden easter eggs 🥚).
- ℹ️ **About Popup** with project details and GitHub link.

---

## 📂 Project Structure
- **index.html** → Main file containing HTML, CSS, and JavaScript.
- **favicons & manifest** → Icons for browsers and devices (`.png`, `.ico`, `.svg`, `site.webmanifest`).
- **notebooks array (inside JS)** → Defines which `.ipynb` files are available to view (fetched from GitHub raw URLs).

---

## 🚀 Usage
1. Clone or download the repository:
   ```bash
   git clone https://github.com/SoultySprings/eda-viewer.git
