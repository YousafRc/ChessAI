ChessAI Game - Final Year Project

Project Overview
This project is a Chess AI game developed as part of my final year dissertation. It implements a chess engine using the Minimax algorithm with Alpha-Beta pruning for efficient AI decision-making. The game also offers additional features, including LAN play via sockets, game logging, and user account management.

Features

-Player vs Player (Local): Two players can play chess on the same computer.

-Player vs AI: Play against the AI, which uses Minimax with Alpha-Beta pruning for intelligent moves.

-LAN Multiplayer: Host or join a session on a local network to play with others.

-Game Logging: A detailed log of all moves made during a game is recorded for later review.

-Account System: Each player has their own account, allowing personalized game experiences.

Game Modes
1. Player vs Player (Local): Two players take turns on the same computer.
2. Player vs AI: Play against the AI with the engine powered by the Minimax algorithm.
3. Join a Session: Join a LAN-hosted game via sockets.
4. Host a Session: Host a game on your local network for others to join.

How to Run the Project:
To run the ChessAI game on your system, download the file onto your computer and run the file main.py

Folder Structure

-Ai.py: Contains the AI logic using Minimax with Alpha-Beta pruning.

-GameBoard.py: Handles the chessboard logic and game state.

-Helper.py: Contains various utility functions to assist the game.

-Move.py: Manages the logic for chess piece movements.

-main.py: The main file to start the game.

-chess_moves_log.txt: Keeps a log of all the moves made during a game.

-chessFirebaseConfig.json: Used for user accounts (possibly Firebase config).

-Fonts/Images: Resources used for the graphical interface.

Dependencies
-Python 3.x
-Additional libraries are listed in the requirements.txt file.

License
This project is for educational purposes and is part of a final year dissertation. For any use outside this context, please contact the author.
