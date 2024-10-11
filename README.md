# Java Swing Calculator

This is a basic arithmetic calculator implemented using Java's Swing and AWT libraries. It features a simple and intuitive graphical user interface (GUI) that allows users to perform addition, subtraction, multiplication, and division operations.

## Features
- **Basic Operations**: Supports addition (`+`), subtraction (`-`), multiplication (`x`), and division (`/`).
- **Error Handling**: Ensures valid arithmetic expressions are evaluated.
- **Clear Display**: Shows the input and result on a scrollable display.
- **Responsive GUI**: Built using Swing components for a modern and interactive user experience.

## How It Works
1. **User Input**: Enter numbers and operations using the calculator's buttons.
2. **Expression Parsing**: The calculator parses the input string into operands and operators.
3. **Evaluation**: Expressions are evaluated based on operator precedence, following the BODMAS rule.
4. **Result Display**: The final result is displayed after pressing the `=` button.

## Installation
1. Clone or download this repository.
2. Compile and run the `Calculate` class:
    ```bash
    javac Calculator.java
    java Calculator 
    ```

## Class Overview
### `Process`
- Handles the parsing and evaluation of arithmetic expressions.
- Checks for valid input and operator sequences.
- Implements the BODMAS rule for evaluating the expression.

### `Calculate`
- Creates the GUI for the calculator.
- Manages user interactions through buttons and displays the input and result.

## Example Usage
1. **Input**: `5 + 3 x 2`
2. **Result**: `11` (BODMAS rule is applied: first multiply, then add)

## Future Improvements
- Add support for advanced operations (e.g., percentages, square roots).
- Implement keyboard input handling for better usability.

## Screenshots
 - Home

![Home](https://github.com/user-attachments/assets/b3d4d1a8-2e83-416d-9a8c-5abc6faadad5)


### Cloning the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/voidAasif/Calculator.git
