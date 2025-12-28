# Java OOP Viking Chess Game

## Overview

This repository contains a **Java implementation of a Viking chess game**, developed as part of an Object‑Oriented Programming (OOP) course assignment.  
The project demonstrates clean object‑oriented design principles using multiple classes interacting to form a board game simulation.

## Topics Covered

This project highlights key OOP concepts including:
- **Classes and Objects**
- **Encapsulation**
- **Inheritance and Interfaces**
- **Polymorphism**
- **Modular design**
- **Game logic separation**

## Repository Structure
```
ConcretePiece.java
ConcretePlayer.java
GUI_for_chess_like_games.java
GameLogic.java
GameLogicTest.java
King.java
Main.java
Pawn.java
Piece.java
PieceKillsCompare.java
PieceLengthCompare.java
PiecePositionCompare.java
PieceSquaresCompare.java
PlayableLogic.java
Player.java
Position.java
test/resources/
viking_chess_screenshot.png
```


- `Main.java` — Entry point of the game simulation.
- `Piece.java`, `King.java`, `Pawn.java` — Core modeling of chess pieces.
- `GameLogic.java`, `PlayableLogic.java` — Game rule logic and turn control.
- Comparator classes (`PieceKillsCompare`, etc.) — Demonstrate use of strategy and comparison patterns.
- `GUI_for_chess_like_games.java` — (If present) handles the graphical or interactive part.
- Tests are in `test/` to validate game logic.

## Technologies

- **Language:** Java  
- **Object‑Oriented Principles:** classes, encapsulation, modular design  
- Basic **Unit Tests** (if included)

## How to Run
Compile and run with your Java compiler or IDE:
```bash
javac *.java
java Main
```

Or in an IDE like IntelliJ / Eclipse:
Open the project folder
Run Main.java as a Java application

## Example Output
![Viking Chess Screenshot](viking_chess_screenshot.png)

## Skills Demonstrated
This project demonstrates:
- Practical object‑oriented programming in Java
- Modeling of a game system as interacting objects
- Application of design principles in a non‑trivial codebase

