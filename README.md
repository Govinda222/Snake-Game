# 🐍 Advanced Canvas Snake Game (Python + PyScript)

This project is an advanced implementation of the classic Snake game, built to run entirely in the web browser using Python and PyScript. It moves beyond wrapper libraries by rendering all graphics directly onto an HTML `<canvas>` element, allowing for higher performance and more complex visual effects.

The game is fully self-contained in a single HTML file and is playable on both desktop and mobile devices.



## ✨ Key Features

* **High-Performance Canvas Rendering:** All game graphics are drawn directly to the HTML Canvas for smooth, efficient animation.
* **Advanced Visuals:** The snake is rendered with rounded segments and 3D-like radial gradients. The food is a custom-drawn apple with a stem.
* **Full Mobile Support:** In addition to keyboard controls (Arrow keys + WASD), the game includes responsive swipe controls for a great experience on phones and tablets.
* **Direct DOM Manipulation:** Python code directly interacts with HTML elements to update the score and handle button clicks, showcasing powerful browser integration.
* **Self-Contained & Portable:** The entire game runs from a single `index.html` file in any modern browser with no backend or installation required.

## 🎮 How to Play

* **Start/Restart:** Press the **"Start / Restart"** button.
* **Desktop Controls:** Use the **Arrow Keys** or **WASD** keys to change the snake's direction.
* **Mobile Controls:** **Swipe** up, down, left, or right on the game canvas to move.
* **Goal:** Eat the red apples to grow your snake and increase your score. Avoid hitting the walls or your own tail!

## 🛠️ Technology Stack

* **Python:** Powers all the game logic, state management, and rendering commands.
* **PyScript / Pyodide:** The framework that runs Python in the browser and provides the bridge to web APIs.
* **HTML & CSS:** Provides the page structure, the `<canvas>` element, and styling for the UI.
* **JavaScript Interoperability:** Uses Pyodide's `js` module and `create_proxy` to interact with browser APIs like `window.setInterval` and handle DOM events (`keydown`, `click`, `touchstart`, etc.).

## 🚀 Deploy Your Own

You can easily host your own version of this game for free using GitHub Pages:

1.  **Create a Repository:** Create a new public repository on GitHub.
2.  **Create the File:** In the repository, create a new file named `index.html`.
3.  **Add the Code:** Copy the complete code for the game into your `index.html` file.
4.  **Enable GitHub Pages:**
    * Go to your repository's **Settings** tab.
    * Click on **Pages** in the left sidebar.
    * Under "Build and deployment", select **Deploy from a branch**.
    * Choose the `main` branch and `/ (root)` folder, then click **Save**.

Your game will be live at `https://govinda222.github.io/Snake-Game/` in a few minutes!
