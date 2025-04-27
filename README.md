# Emerging Systems Architecture and Technologies Projects

## Overview
This repository showcases two projects developed as part of my coursework in emerging systems architecture and technologies. These projects demonstrate my ability to write interface software to control hardware components, analyze hardware architecture designs, and recommend emerging systems architectures based on business requirements.

## Projects Included
- **Smart Thermostat Prototype (Raspberry Pi 4B)**
- **Morse Code LED Blinker with Multithreading**

---

## Reflection

### Summarize the project and what problem it was solving.

The **Smart Thermostat Prototype** project involved designing and implementing a functional thermostat system using a Raspberry Pi 4B. It reads room temperature, allows mode switching (Heat, Cool, Off), adjusts the set point, provides real-time feedback on LEDs and an LCD, and simulates cloud data streaming over UART. It addressed the problem of creating a cost-effective, reliable, and connected smart thermostat suitable for future production.

The **Morse Code LED Blinker** project focused on building an LED signaling system that could transmit Morse code messages while maintaining system responsiveness to user input. It solved the problem of executing concurrent tasks (LED blinking and user interaction) without blocking, ensuring a responsive real-time embedded application.

### What did you do particularly well?

I successfully implemented multithreaded designs to maintain responsiveness in both projects, a critical skill in embedded systems. I also carefully evaluated hardware options for the smart thermostat, providing a justified recommendation based on power consumption, memory capacity, and cloud connectivity needs.

### Where could you improve?

In future iterations, I could further optimize memory usage and implement more advanced fault-tolerance features, such as watchdog timers or fail-safe modes for error conditions. In the Morse code project, adding more sophisticated serial input error handling would make the system even more robust.

### What tools and/or resources are you adding to your support network?

I added practical experience with PySerial for handling serial communication and deepened my familiarity with multithreading in Python for hardware control.
### What skills from this project will be particularly transferable to other projects and/or course work?

Skills in multithreading, hardware interface programming (GPIO, I²C, PWM, UART), real-time system design, and architectural evaluation are highly transferable to future embedded systems, IoT projects, and software engineering tasks where hardware interaction is important.

### How did you make this project maintainable, readable, and adaptable?

I used modular code structures, separating hardware control, user interface logic, and communication handling into distinct components. I also commented thoroughly and followed state machine design patterns where appropriate, making the systems easy to expand (e.g., adding more modes or messages) without requiring a full redesign.
