Here's a README file for your Java GUI Calculator project:

---

# Simple Calculator with Java GUI

## Overview

This project is a simple calculator application built using Java Swing for the graphical user interface (GUI). It provides basic arithmetic operations such as addition, subtraction, multiplication, and division, along with functionalities for clearing the input, deleting the last character, and toggling the sign of the number.

## Features

- **Basic Arithmetic Operations**: Addition, Subtraction, Multiplication, and Division.
- **Decimal Support**: Allows decimal numbers.
- **Clear Function**: Clears the current input.
- **Delete Function**: Deletes the last character of the current input.
- **Negative Toggle**: Toggles the sign of the current number.

## Installation and Setup

1. **Clone the Repository**: 
    ```sh
    git clone https://github.com/yourusername/JavaCalculator.git
    ```
2. **Navigate to the Project Directory**:
    ```sh
    cd JavaCalculator
    ```
3. **Compile the Code**:
    ```sh
    javac Calculator.java
    ```
4. **Run the Application**:
    ```sh
    java Calculator
    ```

## Usage

Once the application is running, you can use the GUI buttons to perform arithmetic calculations:

- **Numeric Buttons (0-9)**: Input numbers.
- **Operation Buttons (+, -, *, /)**: Select an arithmetic operation.
- **Decimal Button (.)**: Add a decimal point to the current number.
- **Equals Button (=)**: Perform the calculation and display the result.
- **Clear Button (Clr)**: Clear the current input.
- **Delete Button (Del)**: Delete the last character of the current input.
- **Negative Toggle Button (-)**: Toggle the sign of the current number.

## Code Explanation

The code is organized as follows:

- **Class Declarations and Imports**: The `Calculator` class implements the `ActionListener` interface to handle button events.
- **Component Initialization**: GUI components such as `JFrame`, `JTextField`, and `JButton` arrays are initialized.
- **Constructor**: Sets up the frame, text field, buttons, and panel layout. Adds action listeners to buttons and sets their fonts and properties.
- **ActionListener Implementation**: Handles button click events, performs the corresponding operations, updates the display, and manages the calculator logic.

### Example Code Breakdown
```java
// Event handling for number buttons
for(int i=0;i<10;i++){
    if (e.getSource() == numberButtons[i]) {
        textfield.setText(textfield.getText().concat(String.valueOf(i)));
    }
}

// Handling operations and other button functionalities
if (e.getSource() == addButton) { /* ... */ }
if (e.getSource() == subButton) { /* ... */ }
if (e.getSource() == mulButton) { /* ... */ }
if (e.getSource() == divButton) { /* ... */ }
if (e.getSource() == equButton) { /* ... */ }
if (e.getSource() == clrButton) { /* ... */ }
if (e.getSource() == delButton) { /* ... */ }
if (e.getSource() == negButton) { /* ... */ }
```

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit pull requests. Contributions are welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

This project was created to brush up on Java skills and to gain hands-on experience with Java Swing and event-driven programming.

---

Feel free to customize the README further based on your preferences or specific details about the project.
