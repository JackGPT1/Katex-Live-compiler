# KaTeX Live Compiler

A clean, responsive, single-page web app for real-time **KaTeX** math equation editing and previewing. Designed for quick math typesetting, deep-learning formula derivations, matrix visualization, and academic note-taking.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![KaTeX Version](https://img.shields.io/badge/KaTeX-v0.16.11-green.svg)
![Pure HTML/JS](https://img.shields.io/badge/Dependencies-Zero-orange.svg)

---

## ✨ Key Features

- **⚡ Real-time Compilation**: Instant math rendering as you type using CDN-delivered KaTeX.
- **↔️ Resizable Split Pane**: Smooth drag handle allowing custom width distribution between code input and live output.
- **⇄ One-Click Panel Swapping**: Swap editor and preview panes instantly without disrupting layout dimensions.
- **🔍 Vector Scale Control**: Smooth vector canvas zoom ($40\%$ to $350\%$) for high-density matrices and detailed equations.
- **🛡️ Non-blocking Error Handling**: Syntax error reporting highlighted cleanly without crashing the application interface.
- **📱 Responsive & Modern UI**: Built with Tailwind CSS and styled with a dark theme for low eye strain.

---

## 🚀 Quick Start

### Option 1: Direct File Open
Simply clone or download this repository, and open `index.html` in any web browser. **No installation or server setup required!**

```bash
git clone https://github.com/your-username/katex-live-compiler.git
cd katex-live-compiler
# Open index.html in your browser
```

### Option 2: Live Local Server
You can serve the web app locally using Python or Node.js:

```bash
# Using Python 3
python -m http.server 8000

# Using Node npx
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## 🛠️ Usage Guide

| Action | Control / Shortcut | Description |
| :--- | :--- | :--- |
| **Type LaTeX / KaTeX** | Left Editor Pane | Input equations (e.g., `\mathbf{A} = \mathbf{B}\mathbf{C}`) |
| **Resize Panels** | Drag Middle Bar | Click and drag the vertical splitter bar |
| **Swap Panels** | Header `Swap Panels` Button | Flips Left/Right workspace layout |
| **Zoom Output** | `＋` / `－` / `Reset` Buttons | Scales rendered vector output from 40% to 350% |
| **Clear Input** | Editor Header `Clear` Button | Erases text in the editor |

---

## 💻 Technical Stack

- **Renderer**: [KaTeX v0.16.11](https://katex.org/)
- **UI Framework**: [Tailwind CSS v3](https://tailwindcss.com/)
- **JS Runtime**: Pure Vanilla JavaScript (DOM Events, CSS Flexbox & Transforms)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).