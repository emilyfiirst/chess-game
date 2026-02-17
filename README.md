# ♟️ Chess Game - Java Console Application

##  About the Project

This project is a **console-based chess application** developed in
**Java**, focused on Object-Oriented Programming (OOP).

The system implements the fundamental chess rules, including:
-   Piece movement
-   Move validation
-   Piece capture
-   Turn control
-   **Check** verification
-   **Checkmate** verification
-   **Castling** special move
-   **En Passant** special move
-   **Promotion** special move

------------------------------------------------------------------------

## Architecture

The project is divided into three main layers:

### boardgame
-  Generic layer responsible for the board structure.

### chess
-  Layer responsible for chess-specific rules.

### application
-  Layer responsible for user interaction.

------------------------------------------------------------------------

## How to Run

### Requirements

-   Java 8 or higher
-   IDE (IntelliJ, Eclipse, VSCode) or terminal

### Running via Terminal

1.  Compile:

``` bash
javac application/Program.java
```

2.  Run:

``` bash
java application.Program
```

------------------------------------------------------------------------

## How to Play

-   The game runs in the console.
-   Moves follow standard chess notation:
```
    Source: e2
    Target: e4
```
The system validates:

-   If the piece belongs to the current player
-   If the move is allowed
-   If the move places the player's own king in check

------------------------------------------------------------------------

## OOP Concepts Applied

-   Encapsulation
-   Inheritance
-   Polymorphism
-   Method overriding
-   Enum usage
-   Exception handling
-   Layered architecture

------------------------------------------------------------------------

## Possible Future Improvements
-   Create a graphical interface (JavaFX or Swing)
-   Add online multiplayer mode

------------------------------------------------------------------------

##  Author

Developed as a Java study project.
