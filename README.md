# TGC-Core-Pico-v2

![Board Render](image_78bedf.png)

## Overview
The **TGC-Core-Pico-v2** is an open-source, IoT-ready hardware development board designed around the Pico architecture (e.g., RP2040). Engineered for high performance, modern connectivity, and sensor [...]

This repository contains the complete set of KiCad EDA files (version 10.0) necessary to view, modify, and manufacture the printed circuit board (PCB).

---

## Key Hardware Features

Based on the schematic and board layout, this board includes the following integrated components and capabilities:

* **Microcontroller:** Pico-compatible architecture featuring a built-in **Temperature Sensor** for internal environmental monitoring.
* **Wireless Connectivity:** Integrated **Wi-Fi** (802.11n) and **Bluetooth** (Classic & BLE), making it perfectly suited for IoT nodes, remote telemetry, and wireless control.
* **Modern Interface:** Upgraded with a **USB Type-C** connector for reliable data transfer and power delivery.
* **Onboard Motion Tracking:** Integrated **ICM-20602** 6-axis MEMS motion tracking device (accelerometer and gyroscope) for robotics, drones, or motion-sensitive applications.
* **Power Regulation:** Onboard **AMS1117-3.3** Low Dropout (LDO) regulator providing a stable 3.3V supply across the board.
* **PCB Specs:** Designed as a 4-layer FR4 board for optimal signal integrity, thermal dissipation, and power routing.

---

## Repository Structure

The project is entirely self-contained within the following native KiCad design files:

| File Name | Description |
| :--- | :--- |
| `TGC-Core-Pico-v2.kicad_pro` | The main **KiCad Project file**. Open this file to load the entire workspace. |
| `TGC-Core-Pico-v2.kicad_sch` | The **Schematic file**. Contains the logical connections, USB-C wiring, wireless modules, regulator, and IMU configuration. |
| `TGC-Core-Pico-v2.kicad_pcb` | The **PCB Layout file**. Contains the physical 4-layer board routing, copper pours, and silkscreen definitions. |
| `image_78bedf.png` | A visual render of the top board design. |

---

## Getting Started

### 1. Viewing and Editing the Hardware
To view or modify the hardware design:
1. Download and install [KiCad EDA](https://www.kicad.org/) (Ensure you are using a modern version compatible with KiCad v10 files).
2. Open the `TGC-Core-Pico-v2.kicad_pro` file.
3. Use the Schematic Editor to view component wiring or the PCB Editor to inspect the board stackup, wireless antenna keep-outs, and routing.

### 2. Manufacturing
You can generate standard manufacturing files (Gerbers, Drill files, BOM, and CPL/Pos files for PCBA) directly from the `TGC-Core-Pico-v2.kicad_pcb` file using KiCad's fabrication output tools.

---

## License

This hardware design and its accompanying documentation are licensed under the **GNU General Public License v3.0 (GPL-3.0-or-later)**.

Summary of your rights under GPLv3:
* You are free to use, study, share, and modify the material.
* If you distribute the work (or a derivative), you must license the whole work under GPLv3 as well (share-alike).
* You must provide source for distributed derivative works and include the GPLv3 license text and copyright notices.

For the full legal text, see the GNU licenses page: https://www.gnu.org/licenses/gpl-3.0.html

Note: To make the change complete, consider adding a `LICENSE` file containing the full GPLv3 text and an explicit copyright line (for example: "Copyright (c) 2026 ThatGuyCodes605"). I can add that file for you if you want.
