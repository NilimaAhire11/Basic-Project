# Calculator Project

## Description

A basic Calculator GUI project developed using Java Swing and AWT.

It performs:
- Addition (+)
- Subtraction (-)
- Multiplication (×)
- Division (÷)
- Percentage (%)
- Positive/Negative (+/-)
- Decimal numbers
- Clear All (AC)

## Technologies Used

- Java
- Java Swing
- Java AWT

## Concepts Used

- Class and Constructor
- Variables
- Arrays
- For Loop
- If-Else Conditions
- Methods
- Type Conversion
- Event Handling
- ActionListener
- JFrame
- JPanel
- JLabel
- JButton
- GridLayout
- BorderLayout

## Important Variables

- buttonValues → Stores all calculator button values.
- rightSymbols → Stores arithmetic operators.
- topSymbols → Stores AC, +/-, and %.
- A → Stores the first number.
- operator → Stores the selected operator.
- B → Stores the second number.

## How the Code Works

1. JFrame creates the calculator window.
2. JLabel is used as the display.
3. buttonValues array stores all button names.
4. A for loop creates the buttons.
5. ActionListener detects button clicks.
6. if-else conditions identify the clicked button.
7. A, operator, and B are used for calculations.
8. Double.parseDouble() converts String values into numbers.
9. The result is displayed using displayLabel.
10. clearAll() resets the calculation values.
11. removeZeroDecimal() removes .0 from whole-number results.

## Code Flow

Button Click  
↓  
ActionListener  
↓  
Get Button Value  
↓  
Check Button Type  
↓  
Perform Required Operation  
↓  
Display Result

## Important Note

The √ button is currently present in the button list, but its functionality has not been implemented yet.

## What I Learned

- Basic Java Swing GUI
- AWT layouts and colors
- Event handling
- Arrays and loops
- Basic calculator logic
- Working with Swing components
