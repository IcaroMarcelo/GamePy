# GamePy

GamePy is a terminal-based math game developed in Python as part of a final course project.

The game generates random mathematical operations based on the difficulty level selected by the player. The user must solve each operation correctly to earn points and can continue playing for multiple rounds.

## Features

- Select a difficulty level
- Generate random numbers according to the selected difficulty
- Generate random mathematical operations
- Addition operations
- Subtraction operations
- Multiplication operations
- Check the player's answer
- Display the correct result
- Track the player's score
- Choose whether to continue playing
- Interactive terminal interface

## Project Structure

```text
GamePy/
├── models/
│   ├── __init__.py
│   └── calcular.py
├── game.py
├── teste.py
├── README.md
├── .gitignore
└── .gitattributes
```

## Main Class

### calcular

The `calcular` class is responsible for generating and managing each mathematical operation.

It stores:

- Difficulty level
- First random value
- Second random value
- Operation type
- Correct result

The class also contains methods responsible for:

- Generating random values
- Calculating the correct result
- Selecting the mathematical symbol
- Displaying the operation
- Checking the player's answer

## Difficulty Levels

The selected difficulty determines the range of numbers used in the mathematical operations.

Higher difficulty levels generate larger numbers, making the operations more challenging.

## Mathematical Operations

The game randomly selects one of the following operations:

```text
Addition       +
Subtraction    -
Multiplication *
```

The correct result is calculated automatically when the operation is created.

## Game Flow

The application follows this general flow:

```text
Start game
↓
Select difficulty
↓
Generate mathematical operation
↓
Display operation
↓
Player enters an answer
↓
Check the answer
↓
Update score if correct
↓
Choose whether to continue
```

## Concepts Practiced

This project was developed to practice:

- Python
- Object-Oriented Programming
- Classes and objects
- Encapsulation
- Properties
- Type Hinting
- Functions
- Conditional statements
- Random number generation
- User input
- Mathematical operations
- Modules and packages
- Score control
- Program flow organization

## How to Run

Clone the repository:

```bash
git clone <repository-url>
```

Enter the project directory:

```bash
cd GamePy
```

Run the application:

```bash
python game.py
```

## Project Status

Completed and functional.
