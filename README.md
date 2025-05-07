# MFC Calculator

A feature-rich calculator application built using the Microsoft Foundation Class (MFC) framework.

## Overview

This calculator provides a user-friendly interface for performing various mathematical operations. It is implemented as a Windows desktop application using the MFC framework in C++.

## Features

- Basic arithmetic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (\*)
  - Division (/)
  - Remainder (%)
  - Power (^)
- Memory function to store and recall previous answers
- Clear function to reset calculations
- Support for decimal numbers
- Error handling for invalid inputs

## Implementation Details

The calculator is implemented as a dialog-based MFC application. The main components include:

- **CCALCULATORDlg**: The main dialog class that handles user input and calculation logic
- **UI Components**: Buttons for digits (0-9), operations, and control functions
- **Input Processing**: Handles both integer and decimal inputs through vector-based storage
- **Operation Logic**: Performs calculations based on user-selected operations
- **Error Handling**: Prevents and displays errors for invalid operations

## Building the Project

### Prerequisites

- Visual Studio with MFC support
- Windows SDK

### Build Steps

1. Open the solution file in Visual Studio
2. Build the solution using the Build menu or F7 key
3. Run the application from Visual Studio or locate the executable in the output directory

## Usage

1. Enter the first number using digit buttons
2. Select an operation (+, -, \*, /, %, ^)
3. Enter the second number
4. Press the equals (=) button to get the result
5. Use the "Ans" button to use previous results in new calculations
6. Press "C" to clear and start a new calculation

## Project Structure

The project follows standard MFC application architecture with dialog resources and corresponding handler classes.

## License

[Add your license information here]
