# Hi, I'm Bassam 👋

Electrical and Computer Engineering student at the **University of Washington Seattle** (GPA: 3.78, graduating May 2028). I build things at the intersection of hardware and software — from custom PCBs and FPGA RTL design to embedded firmware and computer vision systems.

---

## 🔧 What I Work With

**Hardware**
`Altium` `KiCad` `FPGA` `Arduino` `Oscilloscope` `Multimeter` `SMD Soldering` `PCB Fabrication` 

**Languages**
`SystemVerilog` `C` `C++` `Python` `MATLAB` `Java`

**Software & Tools**
`OpenCV` `PySerial` `NumPy` `SolidWorks` `Git` `CAD` `LTspice`

---

## 🚀 Projects

### ✈️ [STM32F405 Quadcopter Flight Controller](https://github.com/bassammorsy/stm32-flight-controller)
Designed a custom 4-layer flight controller PCB from scratch in KiCad targeting Betaflight compatibility with 4S–6S LiPo input. Integrated 5 peripheral sensors across SPI, I2C, and UART buses — ICM-42688-P IMU, BMP388 barometer, QMC5883L magnetometer, SAM-M10Q GPS, and AT7456E OSD. Implemented a two-stage power architecture with a TPS54360DDA buck converter and SPX3819 LDO, calculated all passive values from datasheets, sourced a 43-component BOM, and submitted for SMT assembly through JLCPCB.

### 🔴 [Automatic Laser Tracking Device](https://github.com/bassammorsy/Automatic-Laser-Tracking-Device)
Real-time computer vision targeting system. Python/OpenCV pipeline detects colored objects at 60fps, maps target pixel coordinates to servo angles, and streams commands over serial at 115200 baud to an Arduino-controlled pan-tilt laser turret.

### 🚗 [Autonomous Line-Following Car](https://github.com/bassammorsy/Autonomous-Line-Following-Car)
Designed a PCB from scratch in KiCad with IR sensors, H-bridge motor drivers, and power regulation. Implemented and tuned a PID control algorithm on Arduino for real-time closed-loop motor control. Debugged full hardware-firmware stack using multimeter probing and serial analysis.

### 🤖 LiDAR Maze-Mapping Car *(Boring Robotics Club)*
Designed a SystemVerilog UART receiver and RTL compute pipeline on an FPGA to deserialize and process 32-bit LiDAR data streams. Extracted distance metrics and passed results to an Arduino navigation controller over UART.

### 🔌 [MSPM0 USB Development Board](https://github.com/bassammorsy/MSPM0-USB-Development-Board)
Designed a 2-layer PCB featuring the TI MSPM0 microcontroller with USB-C via CH340 UART bridge. Routed 61 nets across 205 pads with dual-layer GND copper pour and I2C header breakout.

---

## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-bassam--morsy-blue?style=flat&logo=linkedin)](https://linkedin.com/in/bassam-morsy)
[![Email](https://img.shields.io/badge/Email-bassam.morsy.m@gmail.com-red?style=flat&logo=gmail)](mailto:bassam.morsy.m@gmail.com)
