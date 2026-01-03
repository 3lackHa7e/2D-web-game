# 🕹️ Single-File HTML5 Platformer

A fully functional 2D platformer game contained entirely within a single HTML file. It features physics-based movement, enemy AI, tile-based level design, and mobile support—all with zero external dependencies.

## ✨ Features

* **⚡ Single File:** HTML, CSS, and JavaScript are all packed into one `index.html`. No build process required.
* **📱 Mobile Compatible:** Automatically detects touch devices and displays on-screen controls.
* **🗺️ ASCII Level Design:** Levels are built using simple text arrays, making them easy to edit.
* **🏃 Physics System:** Includes gravity, friction, collision detection, and double-jumping.
* **🎨 Theming:** Colors are managed via CSS variables for easy reskinning.

## 🎮 Controls

### Desktop (Keyboard)

* **Move:** Arrow Keys or WASD
* **Jump:** Spacebar, Up Arrow, or W
* **Pause:** P or Esc

### Mobile (Touch)

* On-screen buttons appear automatically on touch devices.

## 🚀 How to Play / Install

Since this is a single-file game, you don't need to install Node.js or run a server.

1. **Download:** simply download the `index.html` file from this repository.
2. **Run:** Double-click `index.html` to open it in any modern web browser.

## 🛠️ Customization

You can easily modify the game by opening `index.html` in a text editor (like VS Code or Notepad).

### 1. Editing Levels

Scroll down to the `const levels = [...]` section in the Javascript. You can draw your levels using characters:

* `.` = Empty Space
* `P` = Platform (Solid)
* `C` = Coin
* `S` = Spike (Hazard)
* `E` = Enemy
* `F` = Player Spawn Point
* `G` = Goal

### 2. Changing Colors

Look for the `<style>` section at the top. Change the hex codes in the `:root` to reskin the game:

```css
:root {
    --bg: #8ecae6;       /* Background Color */
    --player: #ffb703;   /* Player Color */
    --enemy: #ef476f;    /* Enemy Color */
    /* ... etc */
}

```

## 📂 Project Structure

```text
/2D-web-game
│
├── index.html      # Contains all Game Logic, UI, and Styles
└── README.md       # Documentation

```

## 🤝 Contributing

Feel free to fork this project and add your own levels! If you create a cool new level design in the code array, submit a Pull Request so we can add it to the game.

## 📄 License

Distributed under the MIT License.

---

**Created by [3lackHa7e](https://www.google.com/search?q=https://github.com/3lackHa7e)**
