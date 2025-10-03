# Setup Guide

## Using Actuator Examples

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-org/actuators-codebase.git
   ```

2. **Select Your Actuator**
   - Navigate to the `actuators/` directory.
   - Choose the actuator and platform folder (e.g. `actuators/Servo/arduino/`).

3. **Upload Example to Your Board**
   - For Arduino: Open the `.ino` file in Arduino IDE and upload to your board.
   - For STM32: Use your preferred development environment to compile and flash the `.c` example.

4. **Wiring**
   - Check the `notes.md` file in each actuator folder for wiring diagrams and instructions.

## Requirements

- Arduino IDE or STM32 development tools
- The actuator and compatible microcontroller
- Basic wiring tools

## Troubleshooting

- Ensure correct wiring and power supply
- Consult datasheets (linked in `notes.md`) for pinouts and specs
