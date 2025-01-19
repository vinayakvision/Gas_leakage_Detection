# Gas Leakage Detection System

This repository contains the simulation files and Arduino code for a gas leakage detection system. The system is designed using an MQ-4 gas sensor, an Arduino UNO, an LCD display, LEDs, and a buzzer. It detects gas leaks and provides audio-visual alerts to ensure safety.

## Features
- **Gas Detection**: Detects gas leakage using the MQ-4 sensor.
- **Audio-Visual Alerts**: Triggers a buzzer and blinks a red LED upon detecting a gas leak.
- **Real-Time Updates**: Displays the status (Gas Detected or No Gas Detected) on an LCD.
- **Simulation**: Fully simulated in Proteus for validation and testing.

## Components Used
- **MQ-4 Gas Sensor**: Used for detecting the presence of gases like methane and LPG.
- **Arduino UNO**: The microcontroller for processing sensor data and controlling outputs.
- **LCD 16x2**: Displays the gas status.
- **LEDs**:
  - Red LED: Blinks when gas leakage is detected.
  - Green LED: Stays ON when no gas is detected.
- **Buzzer**: Sounds an alarm when gas leakage is detected.
- **Potentiometer**: Adjusts the contrast of the LCD.

## Circuit Diagram
The circuit diagram for the gas leakage detection system is included in the repository as a Proteus design file and an image (`block diagram.png`).

## How It Works
1. The MQ-4 sensor monitors the environment for gas leakage.
2. If gas is detected:
   - The red LED blinks.
   - The buzzer turns ON.
   - The LCD displays "GAS DETECTED ALERT ALERT !!".
3. If no gas is detected:
   - The green LED stays ON.
   - The buzzer remains OFF.
   - The LCD displays "NO GAS DETECTED".

## Getting Started
### Prerequisites
- Arduino IDE
- Proteus Design Suite (for simulation)

-Open the Arduino code (gas_leakage_detection.ino) in the Arduino IDE.
-Upload the code to an Arduino UNO.
-Open the Proteus simulation file (gas_leakage_detectionProject.pdsprj) in Proteus.
-Run the simulation to test the system.

## Hardware Implementation
#### To implement the system on hardware:
- Assemble the components as per the circuit diagram.
- Upload the Arduino code to the Arduino UNO.
- Power the circuit and observe the functionality.

Files Included
- gas_leakage_detection.ino: Arduino code for the project.
- gas_leakage_detectionProject.pdsprj: Proteus simulation file.
- block diagram.png: Circuit diagram image.

Demonstration
- The simulation in Proteus validates the functionality of the gas leakage detection system.
- The hardware implementation can further enhance the project for real-life applications.

Applications
- Home safety systems
- Industrial gas monitoring
- LPG cylinder leak detection

Contribution
Feel free to submit issues or pull requests to improve the project.

