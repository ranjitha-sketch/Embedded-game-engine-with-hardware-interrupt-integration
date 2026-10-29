# 🎮 Embedded Game Engine with Hardware Interrupt Integration

An ESP32-based embedded gaming system that combines interactive gameplay with hardware interrupt handling. The project features three classic games—Dino, Snake, and Pong—using a TFT display, joystick, and push buttons to provide a real-time gaming experience.

## Features

- **Multiple Games** – Play Dino, Snake, and Pong.
- **Hardware Interrupts** – Enable responsive input handling using interrupts.
- **TFT Display** – Display game graphics and animations.
- **Joystick Control** – Control game movements interactively.
- **Push Button Inputs** – Navigate menus and perform game actions.
- **Game State Management** – Handle menu, gameplay, and game-over screens.
- **Collision Detection** – Detect collisions and manage game events.
- **Real-Time Interaction** – Demonstrate responsive embedded system behavior.

## How to Use

1. Connect the ESP32, TFT display, joystick, and push buttons according to the circuit design.
2. Install the required libraries in the Arduino IDE.
3. Open the project source code.
4. Select the correct ESP32 board and COM port.
5. Upload the code to the ESP32.
6. Power on the system and select a game from the main menu.
7. Use the joystick and buttons to play.

## Hardware Components

- ESP32 Development Board
- ILI9341 TFT Display
- Joystick Module
- Push Buttons
- Breadboard and Jumper Wires
- USB Cable and Power Supply

## Technologies Used

- **Programming Language:** C/C++
- **Microcontroller:** ESP32
- **Display Interface:** SPI
- **Graphics Libraries:** `Adafruit_GFX.h`, `Adafruit_ILI9341.h`
- **Communication Library:** `SPI.h`

## Key Concepts

- Hardware Interrupts
- Finite State Machines
- Real-Time Input Processing
- Collision Detection
- Game Physics and Movement
- SPI Communication
- Embedded System Design

## Objective

To develop an interactive embedded gaming platform that demonstrates hardware interrupt integration, real-time input handling, graphics rendering, and game logic using the ESP32 microcontroller.

## Future Enhancements

- Add more interactive games.
- Improve graphics and animations.
- Optimize display rendering to reduce flicker.
- Add sound effects and a high-score system.
- Improve interrupt handling and gameplay performance.

## Author

**Ranjitha Khatawkar**

[GitHub Profile](https://github.com/ranjitha-sketch)
