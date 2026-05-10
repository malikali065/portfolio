# 🌌 Ali Malik | Personal Portfolio

> A calm digital space where minimalist aesthetics meet high-performance code.

Welcome to the repository of my personal portfolio website. This project reflects my passion for clean design, interactive user experiences, and robust frontend architecture. It is built entirely without heavy frontend frameworks to ensure maximum performance and granular control over every animation.

[**Live Demo**](https://your-live-link-here.com) ---

## ✨ Key Features

This portfolio is not just a static page; it's a fully interactive experience designed with a "Cozy Dark" aesthetic.

* **Liquid Glass UI:** Custom glassmorphism effects with ultra-low opacity and high blur for a modern, non-intrusive look.
* **In-Browser Python Engine:** Integrated **Pyodide** (WebAssembly) allows users to execute Python code snippets directly inside the project modal—without a backend server.
* **Procedural Audio Engine:** Sound effects (SFX) are synthesized purely via the **Web Audio API** (Oscillators/Gains), requiring no external audio assets.
* **Material You Volume Control:** A custom-built, liquid-style volume slider with auto-fading visibility to keep the UI clean.
* **Ambient Background:** A custom HTML5 Canvas particle system combined with CSS-animated glowing orbs and a subtle noise grain overlay.
* **Data Visualization:** Smooth, animated radar charts utilizing **Chart.js** to visualize technical skills.

## 🛠️ Tech Stack

This project was built from the ground up focusing on native web technologies:

* **Markup & Styling:** HTML5, CSS3 (CSS Variables, Flexbox/Grid, Animations)
* **Logic & Interaction:** Vanilla JavaScript (ES6+)
* **Libraries/APIs:**
  * [Chart.js](https://www.chartjs.org/) - For the skill radar chart
  * [Pyodide](https://pyodide.org/en/stable/) - CPython compiled to WebAssembly
  * [Highlight.js](https://highlightjs.org/) - For syntax highlighting in code blocks
  * Native Web Audio API - For sound synthesis
* **Typography:** [Sora](https://fonts.google.com/specimen/Sora) (Headings) & [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Body)

## 🚀 Local Development

Since this project is built with Vanilla JS, there is no build step required. However, due to browser security policies (CORS) regarding WebAssembly (Pyodide) and the Web Audio API, it is highly recommended to serve the file via a local web server rather than opening it directly from the file system.

**Using VS Code:**
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
2. Right-click `index.html` and select **"Open with Live Server"**.

**Using Python:**
```bash
# Clone the repository
git clone [https://github.com/yourusername/portfolio.git](https://github.com/yourusername/portfolio.git)
cd portfolio

# Start a local server
python3 -m http.server 8000
