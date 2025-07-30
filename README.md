# 3D-Chess
comp chess


# 3D Chess Game

A fully interactive 3D chess game built with **Three.js** and **chess.js**. Play against a multi-level AI opponent right in your browser.

![3D Chess Game Screenshot](https://placehold.co/600x400/87ceeb/ffffff?text=3D+Chess+Game)
![PLAY]([https://pdragonlabs.github.io/3D-Chess/))

---

## Features

- **Interactive 3D Board**: A beautifully rendered 3D chessboard and pieces.
- **Full Camera Control**: Use your mouse to orbit, pan, and zoom around the board.
- **4 AI Difficulty Levels**:
    - **Level 1**: Makes random legal moves.
    - **Level 2**: A greedy AI that prioritizes captures.
    - **Level 3 & 4**: A challenging AI using the minimax algorithm to think ahead.
- **Move Highlighting**: Click on a piece to see all its valid moves highlighted on the board.
- **Real-time Status Updates**: The UI keeps you informed about the game state, including whose turn it is, checks, and checkmates.
- **Responsive Design**: The game interface adapts to different screen sizes.

---

## How to Play

1.  **Open the `index.html` file** in your web browser.
2.  **Select a Difficulty Level** from the UI panel on the left. The game will automatically start.
3.  You are playing as **White**.
4.  **Click on one of your pieces** to select it. All legal moves for that piece will be highlighted in green.
5.  **Click on a highlighted square** to move your piece.
6.  The AI (Black) will automatically make its move after yours.
7.  The game ends when one player is in checkmate or the game is a draw.
8.  Click the **"New Game"** button at any time to restart.

---

## Technologies Used

-   **HTML5**: The structure of the web application.
-   **Tailwind CSS**: For styling the user interface.
-   **JavaScript (ES6+)**: For all game logic and interactions.
-   **Three.js**: A 3D graphics library used to render the chessboard and pieces.
-   **chess.js**: A powerful library for chess move generation, validation, and game state management.

---

## Local Setup

To run this project on your local machine, simply follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/3d-chess-game.git](https://github.com/your-username/3d-chess-game.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd 3d-chess-game
    ```
3.  **Open `index.html` in your browser.**
    -   You can do this by double-clicking the file in your file explorer.
    -   Alternatively, you can use a local web server or a tool like the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VS Code for the best experience.
