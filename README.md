# Ruthunjay Arduino Projects

# Binary Number Display System

This Arduino project allows you to input a decimal number through the serial monitor and displays its binary representation using LEDs connected to digital pins. Each LED represents a binary digit of the entered number, and the system illuminates the corresponding LEDs to show the binary value.

## Features

- Converts a decimal number to its binary representation.
- Displays the binary representation using LEDs.

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- 5 LEDs
- 5 resistors (for LEDs)
- Jumper wires

## Setup

1. Connect the LEDs to digital pins 8 through 12 on the Arduino board.
2. Connect resistors in series with the LEDs for current limiting (appropriate resistance values should be chosen based on LED specifications).
3. Upload the provided code (`binary_number_display.ino`) to the Arduino board using the Arduino IDE.
4. Open the Arduino serial monitor at a baud rate of 9600 to input decimal numbers and observe the binary representation.

## Usage

1. Open the Arduino serial monitor and type a decimal number you want to convert to binary.
2. Press Enter to send the number to the Arduino.
3. The LEDs connected to pins 8 through 12 will light up to represent the binary value of the entered decimal number.

## Code Explanation

The Arduino sketch consists of two main functions: `setup()` and `loop()`. The `setup()` function initializes the pins for LEDs and starts the serial communication. The `loop()` function continuously reads input from the serial monitor, converts the decimal number to its binary representation, and illuminates the corresponding LEDs.

The code uses bit manipulation techniques to extract individual bits of the binary representation.

## Future Enhancements

This project can be further improved by incorporating the following enhancements:
- Adding more LEDs to accommodate larger binary numbers.
- Implementing a user interface using a display to show both decimal and binary representations simultaneously.
- Allowing the user to input binary numbers for conversion to decimal.

Feel free to modify and expand upon the code to enhance its functionality and usability.

## License

This project is licensed under the [MIT License](LICENSE).
