Classic Snake Game (HTML5 Canvas)
A lightweight, browser-based implementation of the classic Snake game built using HTML5 Canvas and JavaScript.


🎮 How to Play
Objective: Eat the red food squares to grow your snake and increase your score.
Controls: Use the Arrow Keys (Up, Down, Left, Right) to navigate.
Game Over: The game ends if you:
Hit the walls of the game board.
Collide with your own tail.
✨ Features
Responsive Input: Built-in logic to prevent the snake from reversing directly into itself.
Dynamic Growth: The snake body follows the head accurately and grows longer with every piece of food consumed.
Grid System: Uses a 20x20 grid (25px block size) for precise movement.
Randomized Food: Food spawns at random coordinates using Math.random().
🛠️ Installation & Setup
No dependencies or servers are required. This project runs directly in any modern web browser.
Clone the repository:
bash
git clone https://github.com
Use code with caution.

Navigate to the folder:
bash
cd snake-canvas-game
Use code with caution.

Run the game:
Open index.html in your favorite browser.
📂 Project Structure
index.html: Contains the <canvas> element and structure.
snake.js: The core logic (Snake movement, collision detection, and rendering).
style.css: Basic styling for the game board alignment and background.
🚀 Improvements for the Future
Add a high-score counter using localStorage.
Implement a "Start Game" button to avoid immediate play on load.
Add difficulty levels (increasing speed as the snake grows).
Replace setInterval with requestAnimationFrame for smoother rendering.
📄 License
This project is open-source and available under the MIT License.
Created as a project to explore the HTML5 Canvas API.