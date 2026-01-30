# Simple Robotic Arm Controller

This project represents our initial foray into PCB design. It features a compact control board equipped with two potentiometers and a tactile button, specifically engineered to interface with a custom-built robotic arm.

---

## Features
* **Dual Potentiometers:** Enables high-precision servo control for smooth movement.
* **Dedicated Button:** Integrated trigger for seamless gripper operation.
* **ATmega328P Microcontroller:** Utilizes the robust AVR architecture for reliable processing.
* **Custom PCB Design:** Professionally routed and developed using **KiCad**.

---

## Technical Details

The core of the system is the **ATmega328P** microcontroller, programmed via the **Arduino IDE**. The firmware translates analog signals from the potentiometers into precise PWM outputs to govern the arm's rotation and reach, while the digital input from the button toggles the gripper mechanism.

### Hardware Configuration
| Component | Primary Function |
| :--- | :--- |
| **Potentiometer 1** | Reach Control |
| **Potentiometer 2** | Extension Control |
| **Tactile Button** | Gripper Actuation (Open/Close) |
| **Microcontroller** | ATmega328P (Standalone configuration) |

---
