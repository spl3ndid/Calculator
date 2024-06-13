# Minimalistic Calculator

A beautifully designed and functional calculator built using HTML, CSS, and JavaScript. This calculator supports both mouse and keyboard interactions, making it easy to use for quick calculations.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Keyboard support for numeric keys, operators, decimal point, Enter key (for equals), Escape key (for clear), and Backspace (for removing the last digit).
- Clean and modern design with smooth animations on button hover.
- Responsive layout that works well on both desktop and mobile devices.

## Demo

![Calculator Screenshot](https://github.com/spl3ndid/Calculator/blob/main/screenshot.png)

## Installation

To run this calculator locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/spl3ndid/Minimalistic-calculator.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd app
    ```

3. **Open the `index.html` file in your web browser:**
    ```bash
    open index.html
    ```

## Usage

Once the calculator is open in your browser, you can interact with it using both mouse and keyboard:

- **Mouse Interaction:** Click on the buttons to input numbers and operations.
- **Keyboard Interaction:**
  - Numeric keys (0-9) to input numbers.
  - Operators (+, -, *, /) for arithmetic operations.
  - `.` for decimal point.
  - `Enter` or `=` to calculate the result.
  - `Escape` to clear the calculator.
  - `Backspace` to remove the last digit.

## Code Overview

### HTML

The HTML file (`index.html`) sets up the basic structure of the calculator, including buttons for numbers, operators, and other controls.

### CSS

The CSS file (`style.css`) provides the styling for the calculator, including layout, colors, fonts, and button animations.

### JavaScript

The JavaScript file (`script.js`) handles the functionality of the calculator, including:
- Managing the state of the calculator.
- Updating the display based on user input.
- Handling button clicks and keyboard events.
- Performing arithmetic calculations.

### Key JavaScript Functions

- **updateDisplay()**: Updates the calculator screen with the current display value.
- **handleNumber(number)**: Handles number inputs.
- **handleOperator(nextOperator)**: Handles operator inputs.
- **resetCalculator()**: Resets the calculator to its initial state.
- **backspace()**: Removes the last digit from the display value.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request.

## Acknowledgements

This project was inspired by the need for a simple yet functional calculator with a beautiful design. Special thanks to the developers and designers who contribute to open-source projects and make such projects possible.

---

**Note:** Replace the placeholder URL in the "Live Demo" section with the actual URL where your calculator is hosted, if applicable.
