# Ewen Connan

Embedded systems & robotics engineering student — ENIB (Brest), final year, Master SIIA (Intelligent and Autonomous Interactive Systems).
Looking for a **20-week end-of-studies internship (Feb → Jul 2027)** in embedded systems, autonomous robotics or applied AI.

I build systems end to end: firmware on the microcontroller, the communication layer, the model, and the operator interface.

---

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Projet-CMV**](https://github.com/ewen-cnn/Projet-CMV) | Test bench for a NiTiNOL shape-memory-alloy engine: STM32 firmware (4 FreeRTOS tasks, ADC, PWM, interrupt-driven UART with ACK/ERR protocol) and a desktop HMI comparing measurements with a real-time thermomechanical model | C · STM32 HAL · FreeRTOS · Rust · Tauri |
| [**Autonomous-Driving-Car**](https://github.com/ewen-cnn/Autonomous-Driving-Car) | Vision-based driving for a miniature vehicle: multi-task CNN (action + motor commands), automatic labelling from motor states, balanced dataset pipeline, unit-tested | Python · PyTorch · pytest |
| [**MCSI_SuperTuxKart**](https://github.com/ewen-cnn/MCSI_SuperTuxKart) | Multimodal game controller: face tracking, colour detection and EMG / vibration / IMU sensors, solo and two-player modes | Python · MediaPipe · OpenCV · Arduino |
| [**PER — autonomous sailing drone**](https://github.com/DeltaGod/PER_MEA_LYINCROYAP) | Ground-station HMI for a sail-powered marine drone: waypoint mission planning, telemetry storage, map display *(team project — my part: HMI redesign, waypoints, database)* | FastAPI · MongoDB · Leaflet |
| [**Windows-Dashboard**](https://github.com/ewen-cnn/Windows-Dashboard) | Native desktop widget dashboard: widget library, drag-and-drop layout, persistent configuration, live weather | Tauri v2 · React · TypeScript |

<!-- TODO: add the STM32 CAN bus sensor network and the ROS 2 mobile robot once public -->

### Technical stack

- **Embedded:** C, C++, STM32 (HAL, FreeRTOS), CAN, UART, I²C/SPI, PCB design
- **Robotics:** ROS 2, micro-ROS, sensor fusion (IMU, Madgwick filter), control
- **AI / vision:** Python, PyTorch, scikit-learn, OpenCV, MediaPipe
- **Software:** Rust, TypeScript, React, Tauri, Qt, FastAPI, Docker, MongoDB, Git
