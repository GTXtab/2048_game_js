# 2048 Game — Retro Puzzle Implementation

A sleek, modern web implementation of the classic addictive 2048 sliding tile puzzle game. Built entirely with vanilla JavaScript, HTML5, and SCSS, this application focuses on framework-free performance, high-fidelity CSS transitions, responsive layouts, and robust state persistence.

🌐 **Live Demo:** [https://gtxtab.github.io/2048_game_js](https://gtxtab.github.io/2048_game_js)

---

## 🚀 Features

### Core Mechanics
* **Classic 2048 Logic:** Fully functional matrix-based game board handling recursive tile shifting, merging math, and dynamic random tile spawning (2s and 4s).
* **Win & Loss Detection:** Real-time state evaluation that triggers dedicated, interactive overlay screens upon reaching the 2048 tile or running out of valid moves.
* **Score Management:** Live score counter calculation synchronized seamlessly with the interface update cycles.

### Advanced Capabilities & UX
* **💾 State Persistence (Local Storage):** Automatically saves the exact grid layout, current score, and all-time high score, preserving the session even on page reloads.
* **📱 Mobile-First Touch Support:** Native touch-event handling with specialized swipe gesture swipe-vector tracking for seamless mobile gameplay.
* **✨ Fluid Animations:** CSS3 transition matrices and hardware-accelerated transforms for tile sliding and scale-up pop merge effects.

---

## 🛠️ Tech Stack & Architecture

* **Core Language:** JavaScript (ES6+ Functional design and strict DOM manipulation)
* **Styling:** SCSS (Sass compilation utilizing clean variable layouts, nesting structures, and keyframe animations)
* **Markup:** HTML5 (Semantic structures optimized for cross-browser stability)
* **Deployment:** `gh-pages` automated static site deployment workflows.

### Directory Structure
```text
2048_game_js/
├── scripts/        # Domain game logic files and swipe handlers
│   └── main.js     # Entry point handling grid loops and event listeners
├── styles/         # Scalable style sheets architecture
│   ├── main.scss   # Main styling entries, variables, and tile keyframes
│   └── main.css    # Production-ready compiled CSS target
├── index.html      # Central entry file (located in root for GitHub Pages)
└── README.md       # Project documentation

```

---

## 📦 Installation & Setup

Ensure you have [Node.js](https://nodejs.org/) installed to handle style compiling.

1. **Clone the repository:**

```bash
git clone [https://github.com/gtxtab/2048_game_js.git]
cd 2048_game_js

```

2. **Compile SCSS Styles:**
Before running, you need to compile the SCSS files into standard browser-readable CSS.
If you use VS Code, launch the **Live Sass Compiler** extension and click **"Watch Sass"**, or compile via terminal:

```bash
npx sass styles/main.scss styles/main.css

```

3. **Run local development environment:**
Launch the project locally using the VS Code **Live Server** extension, or simply open `index.html` directly in your favorite modern web browser.

---

## 📄 License

This project is open-source software licensed under the **MIT License**. Developed as a technical front-end portfolio piece.
