# STM32F405 Custom Flight Controller PCB

> A custom-designed STM32F405-based PCB for embedded systems, robotics, UAVs, and real-time control applications.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![MCU](https://img.shields.io/badge/MCU-STM32F405RG-green)
![EDA](https://img.shields.io/badge/Designed%20With-EasyEDA-orange)
![Status](https://img.shields.io/badge/status-Development-orange)

---

# 📌 Overview

This project is a custom PCB built around the **STM32F405** microcontroller, intended for high-performance embedded applications such as:

- UAV / Drone Flight Controllers
- Robotics Systems
- Autonomous Vehicles
- Sensor Fusion Platforms
- Real-Time Control Systems

The board is designed with a focus on:

- Compact layout
- Reliable power architecture
- Expandability
- Debugging accessibility
- High-speed peripheral support

---

# ✨ Features

- ⚡ STM32F405RGT6 ARM Cortex-M4 MCU
- 🔌 USB Type-C interface
- 🧭 IMU sensor support (I2C / SPI)
- 📡 Multiple UART ports for telemetry, GPS, receiver, etc.
- 🎮 PWM outputs for ESCs / Servos
- 💾 SPI Flash / External peripherals support
- 🛠 SWD programming interface
- 🔋 Dedicated power regulation circuitry
- 📈 ADC inputs for voltage/current sensing
- 🚁 Designed for Betaflight / Ardupilot experimentation
- 🧩 Modular expansion headers

---

# 🖼 PCB Preview

> Add renders/screenshots here

```text
/docs/render_top.png
/docs/render_bottom.png
/docs/schematic.png
```

---

# 📂 Project Structure

```bash
STM32F405-Custom-PCB/
│
├── Hardware/
│   ├── Schematic/
│   ├── PCB/
│   ├── Gerbers/
│   └── BOM/
│
├── Firmware/
│   ├── Drivers/
│   ├── Core/
│   └── Bootloader/
│
├── Docs/
│   ├── Images/
│   └── Datasheets/
│
└── README.md
```

---

# 🔧 Hardware Specifications

| Component | Description |
|---|---|
| MCU | STM32F405RGT6 |
| Core | ARM Cortex-M4 @ 168 MHz |
| Flash | 1 MB |
| RAM | 192 KB |
| USB | USB Type-C |
| Debugging | SWD |
| Communication | UART / SPI / I2C / CAN |
| Input Voltage | 5V / VBAT |
| Logic Level | 3.3V |

---

# 🔌 Pinout Highlights

| Peripheral | Usage |
|---|---|
| UART1 | Telemetry |
| UART2 | GPS |
| UART3 | Receiver |
| SPI1 | IMU |
| I2C1 | Sensors |
| ADC | Battery Monitoring |
| PWM Outputs | ESC Control |

---

# ⚙️ Firmware Support

Planned firmware compatibility:

- Betaflight
- Ardupilot
- Custom STM32 HAL firmware
- FreeRTOS-based applications

---

# 🛠 Development Tools

Recommended tools used during development:

- KiCad
- STM32CubeIDE
- STM32CubeMX
- ST-Link V2
- CubeProgrammer

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/STM32F405-Custom-PCB.git
```

## 2. Open PCB Files

Open the project in **KiCad**.

## 3. Flash Firmware

Use:

- ST-Link
- DFU Mode
- UART Bootloader

Depending on the firmware configuration.

---

# 📋 Future Improvements

- Blackbox logging support
- OSD integration
- CAN peripherals
- Better power filtering
- Integrated current sensor
- Onboard barometer
- External flash memory

---

# 📸 Gallery

> Add project images, assembled PCB photos, oscilloscope captures, and testing videos here.

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to:

- Open issues
- Submit pull requests
- Suggest improvements
- Report hardware bugs

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ramanuj Agarwal**

Embedded Systems | UAV Electronics | Flight Controller Design | Power Electronics

---

# ⭐ Support

If you found this project useful:

- Star the repository
- Share feedback
- Fork and improve it

---

> Built with caffeine, debugging pain, and excessive datasheet reading.

