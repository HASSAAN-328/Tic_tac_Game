# 🎮 Tic Tac Toe Game

A simple and interactive **Tic Tac Toe game** built using **HTML, CSS, and JavaScript**. This project demonstrates basic DOM manipulation, event handling, and game logic implementation in JavaScript.

🌐 Live Demo

🔗 https://hassaan-328.github.io/Tic_tac_Game/

## 🚀 Features

* Two-player gameplay (Player **O** vs Player **X**)
* Real-time winner detection
* Game reset functionality
* New game option
* Clean and responsive UI
* Disabled boxes after selection to prevent overwriting

## 🛠️ Technologies Used

* **HTML5** – Structure of the game
* **CSS3** – Styling and layout
* **JavaScript (Vanilla JS)** – Game logic and interactivity

## 🎯 How It Works

* The game consists of a **3×3 grid**.
* Players take turns clicking on boxes:

  * Player O starts first
  * Then Player X
* Once a box is clicked, it becomes disabled.
* The game checks for winning combinations after each move.
* When a player wins:

  * A message is displayed
  * (Optional improvement: disable all boxes)
* Users can:

  * Click **Reset Game** to clear the board
  * Click **New Game** to restart fresh

## 🧠 Winning Logic

The game uses predefined winning patterns:

```
[0,1,2], [0,3,6], [0,4,8],
[1,4,7], [2,5,8], [2,4,6],
[3,4,5], [6,7,8]
```

If any pattern matches the same symbol (O or X), that player wins.

## 📁 Project Structure

```
📦 Tic-Tac-Toe
 ┣ 📜 index.html   # Game layout
 ┣ 📜 style.css    # Styling
 ┣ 📜 app.js       # Game logic
 ┗ 📜 README.md    # Project documentation
```

## ▶️ How to Run

1. Download or clone the repository:

   ```
   git clone https://github.com/your-username/tic-tac-toe.git
   ```
2. Open `index.html` in your browser.

## 🔧 Possible Improvements

* Add draw/tie detection
* Disable all boxes after a win
* Add sound effects
* Add AI (single-player mode)
* Improve animations

## 📸 Preview

A clean UI with a centered 3×3 grid and interactive buttons for reset and new game.

## 📜 License

This project is open-source and available for learning and practice.

---
