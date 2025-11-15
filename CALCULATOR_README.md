# Scientific Calculator

A fully-functional scientific calculator built with HTML, CSS, and JavaScript. This calculator provides both basic arithmetic operations and advanced scientific functions.

## Features

### Basic Operations
- **Addition (+)**: Add two numbers
- **Subtraction (−)**: Subtract two numbers
- **Multiplication (×)**: Multiply two numbers
- **Division (÷)**: Divide two numbers
- **Decimal points**: Support for decimal numbers

### Scientific Functions
- **Trigonometric Functions**: sin, cos, tan (with degree/radian mode toggle)
- **Logarithmic Functions**: ln (natural log), log (base 10)
- **Mathematical Constants**: π (pi), e (Euler's number)
- **Power Functions**: 
  - x² (square)
  - xʸ (power)
  - √ (square root)
- **Other Functions**:
  - 1/x (reciprocal)
  - n! (factorial)
- **Parentheses**: Support for complex expressions with ( and )

### User Interface Features
- **Clear (C)**: Reset the calculator
- **Backspace (←)**: Delete the last character
- **DEG/RAD Toggle**: Switch between degree and radian modes for trigonometric functions
- **Dual Display**: Shows both the expression and the result
- **Keyboard Support**: Use your keyboard for faster input

## How to Use

### Opening the Calculator
Simply open `calculator.html` in any modern web browser. No installation or dependencies required!

### Basic Calculations
1. Enter numbers using the number buttons (0-9)
2. Click an operator (+, −, ×, ÷)
3. Enter the second number
4. Press = to see the result

**Example**: `5 + 3 = 8`

### Scientific Functions
Most scientific functions work on the current displayed value:

1. **Square Root**: Enter `16`, then click `√` → Result: `4`
2. **Square**: Enter `5`, then click `x²` → Result: `25`
3. **Factorial**: Enter `5`, then click `n!` → Result: `120`
4. **Sine**: Enter `90`, ensure "DEG" mode, click `sin` → Result: `1`
5. **Reciprocal**: Enter `4`, click `1/x` → Result: `0.25`

### Using Constants
- Click `π` to insert pi (3.14159...)
- Click `e` to insert Euler's number (2.71828...)

**Example**: `2 × π = 6.28318...`

### Complex Expressions
You can create complex expressions using parentheses:

**Example**: `(5 + 3) × 2 = 16`

### Keyboard Shortcuts
- **Numbers**: 0-9
- **Operators**: +, -, *, /
- **Decimal**: .
- **Calculate**: Enter or =
- **Clear**: Escape or C
- **Backspace**: Backspace key
- **Parentheses**: ( and )

### Degree vs Radian Mode
- Click the `DEG` button to toggle between degree and radian modes
- In **DEG** mode: trigonometric functions use degrees
- In **RAD** mode: trigonometric functions use radians

## Examples

### Basic Arithmetic
```
12 + 8 = 20
15 - 7 = 8
6 × 9 = 54
20 ÷ 4 = 5
```

### Scientific Calculations
```
√144 = 12
5² = 25
2^3 (using xʸ) = 8
5! = 120
sin(30°) = 0.5
ln(e) = 1
log(100) = 2
```

### Complex Expressions
```
(10 + 5) × 2 = 30
√(16 + 9) = 5
2 × π = 6.283...
```

## Technical Details

- **Self-contained**: Single HTML file with embedded CSS and JavaScript
- **No dependencies**: Works without internet connection
- **Browser compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **Responsive design**: Adapts to different screen sizes

## Implementation Highlights

- Object-oriented JavaScript design with a `ScientificCalculator` class
- Real-time expression evaluation
- Floating-point precision handling
- Error handling for invalid operations
- Smooth animations and hover effects
- Keyboard event handling for improved user experience

## Limitations

- Very large numbers may be displayed in scientific notation
- Factorial function works only with non-negative integers
- Expression evaluation uses JavaScript's native math functions

---

**Created for**: GitHub Skills - Introduction to GitHub
