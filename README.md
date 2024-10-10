# Logisim Calculator

## Overview
This is a simple calculator project built using [Logisim](http://www.cburch.com/logisim/), a digital circuit simulator. The calculator can perform basic arithmetic operations such as addition, subtraction, multiplication, and division using binary numbers. My idea is expand to support n-bit operations, modulo, exponentiation, bitwise operations, comparisons

## Features
- **4-bit Binary Addition**
- **4-bit Binary Subtraction**
- **4-bit Binary Multiplication**
- **4-bit Binary Division**
- **Overflow Detection**: The calculator detects overflow conditions in addition and subtraction.
- **Clear Function**: A reset functionality to clear the inputs and results.

## Circuit Design
The calculator is designed using basic logic gates, multiplexers, and arithmetic circuits such as:
- **4-bit adder**: Used for binary addition.
- **4-bit subtractor**: Used for binary subtraction (implemented with an adder and two's complement logic).
- **Multiplier**: For multiplication operations.
- **Divider**: To perform binary division.
- **Multiplexer**: Used to select between different operations based on control inputs.
- **Display Unit**: Shows the results in binary form, with LEDs representing bits.

## Project Files
- `calculator.circ`: The main Logisim circuit file for the calculator.
- `README.md`: This documentation file explaining the project.

## How to Use
1. **Open the Project**:
   - Download and install Logisim (if you don't have it already).
   - Open `calculator.circ` in Logisim.

2. **Input Values**:
   - Use the input switches to set the binary values for the operands.
   - Set the control switches to choose the desired operation:
     - `00`: Addition
     - `01`: Subtraction
     - `10`: Multiplication
     - `11`: Division

3. **View Output**:
   - The output LEDs will show the result in binary.
   - Overflow LEDs indicate if there's an overflow during the operation.

4. **Reset**:
   - Press the reset button to clear all inputs and outputs.
