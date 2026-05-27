# Lab 4 - Tic-Tac-Toe Computer Player

This repository contains my Lab 4 project for CPSC 440 Game Programming.

## Description

This project modifies the provided Tic-Tac-Toe starter code so that the human player controls X and the computer controls O.

The computer player uses simple random movement. After the human player places an X, the computer randomly chooses a location on the playable board and attempts to place an O. If the selected square is already taken, the computer keeps trying until it finds an open square.

## Features

- Human player controls X with mouse clicks
- Computer automatically plays O
- Computer randomly selects playable board locations
- Game checks for X win, O win, and tie
- Game displays a message when the game ends
- Uses Allegro graphics, primitives, fonts, and mouse input
- Loads the font once at startup and reuses it for game messages

## How to Run

1. Open the `.sln` file in Visual Studio.
2. Make sure Allegro is installed through NuGet.
3. Make sure the required Allegro add-ons are enabled.
4. Make sure `GROBOLD.ttf` is included with the project.
5. Build and run the project.
6. Click a square to place X. The computer will automatically place O.

## Controls

- Left mouse click: Place X on an open square
- Close window: Exit the game

## Author

Christian Toliver
