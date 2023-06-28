# Project Description

This project showcases a simple yet classic game of "Pong" implemented using Python's turtle module. The game features a black game window with two white paddles and a bouncing ball. Players control the paddles with the goal of keeping the ball within the game area. Points are awarded when one player fails to return the ball and it touches their edge of the screen.

## Key Features

- **Two Player Game**: Player A uses the 'w' and 's' keys to move their paddle up and down respectively. Player B uses the 'Up' and 'Down' arrow keys for the same purpose.
- **Scoring**: The game keeps track of each player's score. When the ball touches one player's edge of the screen, the other player is awarded a point. The current score is displayed at the top of the screen.
- **Winning Condition**: The game ends when one player reaches a predetermined winning score (5 in this case). A game over message is then displayed, indicating the winner.
- **Game Reset**: After a game ends, players can press the 'r' key to reset the game. This action resets the scores, positions the ball and paddles back at their starting locations, and restarts the game.
- **Visual and Sound Effects**: The game offers a visual aesthetic reminiscent of the original Pong game, featuring a black background, white paddles, and a white ball. Sound effects are also included to enhance gameplay experience; these are activated when the ball bounces.

## Technologies Used

- **Python**: The game is written entirely in Python, leveraging its built-in modules.
- **Turtle**: This Python module is used for the game's graphical output and keyboard input handling.
- **os Module**: The os module is used to play sound effects during the game. The "afplay" command is specific to MacOS, so this feature might not work on other operating systems.
- **Infinite Loop**: The main game loop, an infinite "while" loop, continually updates the game window, moves the ball, checks for collisions, updates the score, and monitors game termination conditions.

## Getting Started

Follow these steps to set up and run the game locally:

1. **Clone the repository:**

    git clone https://github.com/DonYoon/pong.git

2. **Change to the project directory:**

    cd pong

3. **Run the game:**

    python pong.py

4. **Enjoy playing Pong!**

