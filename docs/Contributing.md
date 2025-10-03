# Contributing to Actuators Codebase

Thank you for your interest in contributing! This repository collects example files for various actuators on platforms like Arduino and STM32. We welcome contributions of new actuator examples, improvements, documentation, and more.

## How to Contribute

### 1. Fork the Repository

Click "Fork" at the top right of the repo page to create your own copy.

### 2. Clone Your Fork

```sh
git clone https://github.com/your-username/actuators-codebase.git
cd actuators-codebase
```

### 3. Add Your Example

- Navigate to the `actuators/` directory.
- Add a new folder for your actuator if it doesn't exist, e.g. `actuators/ActuatorX/`.
- Inside the actuator folder, add code examples for each supported platform:
  - `arduino/` for Arduino sketches
  - `stm32/` for STM32 C source files
- Include a `notes.md` with wiring, datasheet links, and any special instructions.

**Example Structure:**

```
actuators/
  ActuatorX/
    arduino/
      example.ino
    stm32/
      example.c
    notes.md
```

### 4. Write Clear, Commented Code

- Make your code readable and well-commented.
- Keep examples simple; focus on actuator usage and setup.
- Add a brief description at the top of each file.

### 5. Add Documentation

- In `notes.md`, describe wiring, pin assignments, actuator features, and datasheet links.

### 6. Update README (if needed)

- If you add a new actuator, mention it in the main `README.md`.

### 7. Open a Pull Request

- Commit your changes.
- Push to your fork.
- Open a Pull Request (PR) from your fork to the main repository.
- In your PR description, explain what you added and any relevant details.

## Review Process

- The maintainers will review your PR.
- You may be asked for changes to fit repo style or improve clarity.
- Once approved, your changes will be merged.

## Code of Conduct

Please be respectful and constructive. See our [Code of Conduct](./CODE_OF_CONDUCT.md) for details.

---

Thank you for contributing!
