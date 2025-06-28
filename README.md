# regenBrakingBike for Arduino
A regenerative braking system for bicycles, designed to recover energy during braking, especially in high climbs, long-distance tours, and urban commuting. It features adjustable regen levels, slope-based activation, and speed-dependent settings for an optimized, eco-friendly riding experience.


# Regen Braking System for High Climb and Touring Bicycles

This project implements a regenerative braking system designed for bicycles, with a focus on enhancing performance during high climbs, long-distance touring, and urban commuting. It takes into account factors such as speed, slope, and cadence, providing an adaptive solution for riders who regularly encounter elevation changes.

## Features
- **Regenerative Braking for High Climb Bicycles:** Efficient braking and energy recovery for bikes used in mountainous terrain and high-elevation climbs.
- **Touring and City Use:** Suitable for long-distance touring bikes and city commuting, especially where elevation differences are significant.
- **Customizable Regen Modes:** Multiple regen levels for different riding conditions, with automatic and manual controls.
- **Slope-Based Activation:** Regen activates based on predefined slope thresholds, optimizing braking and power regeneration during downhill sections.

## Setup
1. **Speed Sensor:** Connect the speed sensor to pin 3 on the Arduino.
2. **Slope Sensor:** Attach the slope sensor to pin A0.
3. **Cadence Sensor:** Connect the cadence sensor to pin A1.
4. **Brake Sensor:** Wire the brake sensor to pin 2.
5. **Upload the Code:** Upload the Arduino sketch (`regen_braking_system.ino`) to your Arduino board.

## Configuration Options
- **Regen Activation Speed:** Regen can be activated at different speed thresholds. Adjustable by the rider for conditions like city commuting or mountain climbing.
- **Slope Sensitivity:** The system can be tuned to activate regenerative braking based on slope readings, ensuring more efficient energy recovery during steep descents.

## Dependencies
- `Wire.h` for I2C communication
- `Encoder.h` for cadence sensor (optional)

## License
This project is **licensed under the MIT License**. You are free to modify, distribute, and use the code in your personal or commercial projects. However, you are not allowed to hold the author liable for any damages resulting from the use of this system.

If you wish to contribute to this project or need support, feel free to open issues or pull requests.

## Important Notes
- This system is intended for use on bicycles where high climbs and long tours are common.
- Proper calibration of sensors and settings is important for optimal performance.
- Always test the system on flat terrain before using it in more complex conditions.

// Ride Safe!
