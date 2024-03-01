# Arduino NAND Gate Implementation

This project implements a NAND gate using an Arduino Uno and LEDs. The circuit consists of two input push buttons, three LEDs for input and output display, and pull-up resistors connected to the push buttons. When a push button is pressed, the corresponding LED toggles its state, and the output LED reflects the NAND gate operation based on the inputs.

## Components Used
1. Arduino Uno
2. LEDs (3x)
3. Push buttons (2x)
4. Resistors (10K Ohm for pull-up, 330 Ohm for LED current limiting)

## Circuit Connections
- Connect the negative (-) terminal of each LED to the ground (GND) of the Arduino Uno.
- Connect the positive (+) terminal of each LED to the designated digital pins of the Arduino Uno.
- Connect one terminal of each push button to the ground (GND) of the Arduino Uno.
- Connect the other terminal of each push button to the designated digital pins of the Arduino Uno. Also, connect each terminal to +5V of the Arduino Uno through a 10K ohm resistor.

## Folder Structure
- **/program:** Contains the Arduino sketch for the NAND gate implementation.
- **/documentation:** Contains detailed documentation for the project.

## Operation
- Pressing a push button toggles the state of the corresponding LED.
- The output LED reflects the NAND gate operation based on the inputs. It remains LOW only when both input LEDs are HIGH; otherwise, it is HIGH.

## Results
The implemented NAND gate circuit demonstrated the expected behavior, accurately toggling the state of the LEDs based on the input push buttons. The output LED correctly reflected the NAND gate operation, remaining LOW only when both inputs were HIGH. The circuit operated reliably without any unexpected behavior observed during testing.
