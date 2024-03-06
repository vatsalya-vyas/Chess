# Chess Console Game in C++

## Overview
This is Chesscomputer v.0.1, a simple console-based chess game with a basic AI opponent. The game is implemented in C++ and provides a text-based interface for playing chess against the computer.

## Screenshot
![Screenshot from 2024-03-06 19-24-29](https://github.com/vatsalya-vyas/Chess/assets/140804211/cf93bab0-42d5-4729-811a-172078a181f6)

## Features
- Human vs. AI gameplay
- Basic AI opponent using the minimax algorithm
- Interactive console-based interface
- Ability to toggle showing coordinates on the chessboard
- Commands for help, quitting, showing the board, and toggling coordinates

## How to Play
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/vatsalya-vyas/Chess.git
    cd Chess
    ```
2. **Run the Code:**
    - Compile and run the C++ code using a suitable compiler. For example:
        ```bash
        g++ chess_game.cpp -o chess_game
        ./chess_game
        ```
3. **Choose Your Side:**
    - Follow the prompts to choose to play as black (b) or white (w).
4. **Make Moves:**
    - Enter your moves in the format `yxyx`, where `yx` represents the coordinates of the piece to move, and `yx` represents the destination coordinates.
5. **Commands:**
    - Use the following commands during the game:
        - `h` or `help`: View the help menu.
        - `q`: Quit the game.
        - `p`: Display the current state of the chessboard.
        - `c`: Toggle coordinates inside squares.

## Example Move
- To move a piece from (1,7) to (1,5), enter `1715` when prompted for a move.

## AI Opponent
- The AI opponent uses a basic implementation of the minimax algorithm with a depth of 4.

## Piece Values
- The game assigns values to each chess piece for scoring purposes:
  - King: 10000
  - Queen: 9
  - Pawns: 1
  - Bishops and Knights: 3
  - Rooks: 5

## Enjoy the Game!
Feel free to explore, improve, or customize this chess game. Enjoy playing against the computer opponent or challenge yourself with a friend! If you encounter any issues or have suggestions for improvements, feel free to contribute or provide feedback. Have fun!
