# Keypad Password Lock

Arduino-based password verification system using a 4x4 keypad.  
Solo project.

## Stack
- Arduino C++
- Keypad library

## Features
- 6-digit password input (default: "123456")
- Real-time serial output for each key press
- Password comparison with strcmp
- Outputs "Correcta" or "Incorrecta" in Serial Monitor
- Resets after 6 digits

## Wiring
- Keypad rows: Pins 9, 8, 7, 6
- Keypad columns: Pins 5, 4, 3, 2

## How to Use
- Upload to Arduino board
- Open Serial Monitor (9600 baud)
- Enter code via keypad
- Extend with servo/relay for physical lock

## Demo
![Circuit Diagram](screenshots/circuit.png)  
![Simulation](https://www.tinkercad.com/things/lnCskaYqijb-p9-yuliya?sharecode=Z4Iqy6ty9iNEEibgNrey3M4O_DSlBYoswIZLY0vppGM)# Keypad-Password-Door-Lock
