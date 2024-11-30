# BLDC Motor Control: FOC Control and Six-Step Commutation

This project demonstrates the control of a Brushless DC (BLDC) motor using two distinct methodologies: **Field-Oriented Control (FOC)** and **Six-Step Commutation**, each offering unique advantages and catering to specific application needs.

---

## Features

- **Field-Oriented Control (FOC):**
  - Precise and smooth motor control.
  - High efficiency and torque control.
  - Low noise and vibration operation.

- **Six-Step Commutation:**
  - Simple implementation.
  - Suitable for applications with lower precision requirements.
  - Robust and reliable control.

---

## Hardware Requirements

- BLDC motor (in my case is [DB28S01 – 	Brushless DC motor](Documents/DB28S01.pdf))
- Microcontroller with PWM generation capability (in my case is [Nucleo-F401RE](https://www.st.com/en/evaluation-tools/nucleo-f401re.html))
- Motor driver or inverter circuit (in my case is [X-NUCLEO-IHM07M1](https://www.st.com/en/ecosystems/x-nucleo-ihm07m1.html))
- Current sensing (optional for FOC)
- Sensors:
    - Hall sensors from the [DB28S01 BLDC motor](Documents/DB28S01.pdf).
    - Renesas [inductive sensor](Documents/REN_IPS2550-Datasheet_DST_20240424.pdf).
- Power supply for the motor

---

## Software Requirements

- Development Environment: Compatible tools such as STM32CubeIDE or Arduino IDE.
- Control Libraries: Include PID controllers and math libraries for FOC algorithms.
- Custom Firmware: Implementing both Field-Oriented Control and Six-Step Commutation methodologies.

