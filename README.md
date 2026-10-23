
# Gökkalkan — Integrated Air Defense System

**TEKNOFEST 2026 | Çelikkubbe Air Defense Systems Competition**

Gökkalkan is a multidisciplinary engineering project developed for TEKNOFEST 2026. It combines computer vision, embedded systems, hardware communication, and a software-based operator interface.

The software is designed around modular components for visual tracking, system monitoring, simulation, and controlled hardware interaction.

## Key Features

- **Operator Interface:** A React and TypeScript dashboard for monitoring system state, camera feeds, and operational controls.
- **Computer Vision:** Camera-based target tracking using OpenCV and Raspberry Pi-based processing.
- **Backend Architecture:** A Python backend for managing commands, system state, and hardware communication.
- **Embedded Integration:** Arduino-based motor control and serial communication with external hardware.
- **Simulation:** Deterministic test scenarios and a digital twin for validating system behavior without physical hardware.
- **Safety and Testing:** Software safety gates, emergency-stop handling, telemetry logging, and automated tests.

## Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | Python, HTTP APIs, SQLite |
| Computer Vision | OpenCV, Raspberry Pi |
| Embedded Systems | Arduino, Serial Communication |
| Testing | Pytest, Simulation, Hardware-in-the-Loop |

## Software Architecture

The system is organized into several components:

1. **Operator Panel:** Provides visualization and user controls.
2. **Backend and Mission Core:** Manages system state, commands, and telemetry.
3. **Perception Module:** Processes camera input and provides tracking information.
4. **Hardware Interface:** Communicates with Arduino-based control components.
5. **Simulation and Testing:** Supports development and validation using mock hardware and reproducible scenarios.

The architecture separates the operator interface, decision logic, perception, and hardware interfaces to improve modularity and testability.

## Development Status

The repository includes an operator interface, backend services, perception components, simulation tools, and embedded integration code.

Software simulation and hardware-in-the-loop testing are supported. Full physical-system validation remains separate from software-level verification.

## Competition

Developed as a team project for the **TEKNOFEST 2026 Çelikkubbe Air Defense Systems Competition**.

## Documentation

Additional technical documentation, system architecture decisions, hardware interfaces, test procedures, and setup instructions are available in the `docs/` directory.
