# Sudoku Game in Assembly

## Overview
This project is a Sudoku game implemented in x86 Assembly language. It features a graphical interface and various functionalities to provide an interactive and engaging experience for the user. The game includes a grid-based layout, user input handling, and visual feedback for gameplay actions.

## Features

### 1. **Graphical Interface**
   - The game displays a visually appealing Sudoku grid using ASCII characters.
   - The grid is dynamically updated based on user actions.
   - Borders, buttons, and other visual elements are rendered to enhance the user experience.

### 2. **Game Modes**
   - **Start Game**: Begin a new Sudoku puzzle.
   - **Help**: Display instructions and rules for playing Sudoku.
   - **Exit**: Quit the game.

### 3. **Dynamic Grid Updates**
   - The game dynamically updates the grid as the user fills in numbers.
   - Empty spaces in the grid are filled with numbers based on user input or predefined logic.

### 4. **Input Handling**
   - The game accepts user input to fill in numbers in the grid.
   - Input validation ensures that only valid moves are allowed.

### 5. **Feedback System**
   - Visual feedback is provided for correct and incorrect moves:
     - **Green**: User-filled numbers that are correct.
     - **Red**: Incorrect moves.
     - **Blue**: Notes or hints.
   - Pre-filled numbers are displayed in black.

### 6. **Timer and Score Tracking**
   - A timer is implemented to track the duration of the game.
   - The score is updated based on the user's performance.

### 7. **Random Number Generation**
   - The game includes a subroutine to generate random numbers for filling the grid or other gameplay elements.

### 8. **Help and Instructions**
   - The game provides detailed instructions on how to play Sudoku.
   - It includes visual examples to guide the user.

### 9. **End Screen**
   - Displays a "Thanks for Playing!" message upon completion.
   - Allows the user to exit the game gracefully.

### 10. **Advanced Features**
   - **Notes System**: Users can add notes to cells for potential numbers.
   - **Reset Functionality**: Reset specific parts of the grid or the entire game.
   - **Save and Restore State**: The game can save and restore the current state, including the grid, score, and other variables.

## Technical Details
- **Assembly Language**: The game is written in x86 Assembly, leveraging low-level programming for precise control over the graphical interface and game logic.
- **Grid Dimensions**: The grid is displayed as a 73x25 layout, with additional sections for instructions and feedback.
- **Subroutines**: Modular subroutines handle tasks such as printing numbers, generating random numbers, and updating the grid.

## How to Play
1. Launch the game in an x86-compatible environment.
2. Select an option from the menu:
   - Start a new game.
   - View help and instructions.
   - Exit the game.
3. Fill in the grid by entering numbers in the appropriate cells.
4. Use the notes system to plan your moves.
5. Complete the puzzle by filling in all cells correctly.

## Requirements
- An x86-compatible emulator or environment (e.g., DOSBox).
- Basic understanding of Assembly language (optional, for debugging or customization).

## Future Enhancements
- Add support for different difficulty levels.
- Implement a hint system to assist players.
- Include a save/load feature for game progress.

Enjoy solving Sudoku with this unique Assembly-based implementation!
