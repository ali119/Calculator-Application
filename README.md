# Calculator Application
We use the Java Language to develop this application
# Java Calculator

A desktop calculator built with Java Swing. It performs basic arithmetic
through a simple graphical interface.

## Features
- Addition, subtraction, multiplication, and division
- Percentage and sign change (+/-)
- Decimal numbers
- Backspace (DEL) and clear (C)
- Divide-by-zero protection (shows "Error")

## Tech
Java (JDK 8+), Swing

## Run
javac Calculator.java
java Calculator

## Testing
Tested manually with:
- Basic operations: 12 + 8 = 20, 9 - 15 = -6, 7 * 6 = 42
- Decimals: 0.1 + 0.2, 5 / 2 = 2.5
- Chained operations: 2 + 3 * 4 (evaluated left to right, like a basic pocket calculator)
- Edge cases: division by zero, multiple decimal points, DEL on a single digit

## Future improvements
- Keyboard input
- Operator precedence
- Calculation history
- Scientific functions
