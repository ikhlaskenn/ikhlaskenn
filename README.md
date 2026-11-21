# Hi, I’m Ikhlass 👋

⚡ Electrical Engineer | Automation & Instrumentation
🎓 MSc student in Electronics, Electrical Energy and Automatic Control (E3A), Université Paris-Saclay
📍 Paris, France
💡 Embedded Systems • FPGA & Digital Design • Industrial Automation

---

## 👩‍💻 About Me

I hold an engineering degree in Electrical Engineering from **Óbuda University** (Budapest), with a specialization in **Automation and Instrumentation**, and I am currently completing an **MSc in E3A at Université Paris-Saclay**.

My work sits where hardware meets software: embedded firmware, real-time control on FPGA, and the measurement and instrumentation side that tells you whether any of it actually works. I care about designs that are verified rather than assumed — bit-exact comparisons against a reference model, timing closure, honest limitations written down.

---

## 🧠 Technical Skills

**Embedded & Hardware**
- ATmega64 / ATmega328P (ADC, PWM, UART, LCD, timers), STM32, ESP32
- Serial buses: UART, I²C; notions of Modbus and CAN
- Sensors: temperature, IMU (MPU6050), analog and digital sensing
- Motor drivers (L298N), differential drive systems
- Schematic capture in Altium Designer

**FPGA & Digital Design**
- VHDL, finite state machines, fixed-point arithmetic
- Intel Cyclone V (DE1-SoC), Quartus II, ModelSim, static timing analysis
- Nios II soft processor, Qsys system integration

**Automation & Instrumentation**
- Siemens S7-1200 PLC
- Two semesters of measurement coursework: oscilloscopes, instrumentation, functional electrical testing
- Signal conditioning, signal and image processing
- V-model development cycle

**Software & Programming**
- C / Embedded C, Python, Bash
- C# (.NET), ASP.NET Core & Orchard Core CMS
- SQLite integration, PDF and Excel report generation
- MATLAB / Simulink

**Tools**
- Quartus II · ModelSim · Microchip Studio · Arduino IDE · Visual Studio · MATLAB · Altium Designer · Git

---

## ⚙️ Featured Project

### [FPGA Hardware-in-the-Loop: DC Motor Simulation and PI Speed Control](https://github.com/ikhlaskenn/fpga-hil-dc-motor)

A DC motor and its PI speed controller, both running in real time on an **Intel Cyclone V FPGA** (DE1-SoC) with no external hardware.

- State-space motor model discretized at 100 µs, computed in **Q12.20 fixed point** in VHDL
- PI controller with output saturation and **integral anti-windup**
- VHDL verified **bit-exact** against a MATLAB reference model (ModelSim testbench, maximum error = 0)
- 2 % of the FPGA logic, 50 MHz with +9.1 ns setup slack

`VHDL` · `Quartus II` · `ModelSim` · `MATLAB`

---

## 🔐 [Secure Access Control System Using Facial Recognition](https://github.com/ikhlaskenn/esp32cam-face-access-control)

A door lock that opens on a face. An **ESP32-CAM** performs detection, feature extraction and matching entirely on-device, then drives a relay that releases a 12 V electromagnetic solenoid lock.

- Fully embedded biometric pipeline — no cloud, templates stay in the module's flash
- Non-blocking unlock timer and fail-secure power-up state
- Hardware integration: relay isolation between 3.3 V logic and the 12 V lock
- Documented limitations: 2D spoofing, lighting sensitivity, and the privacy implications of biometric data

`C/C++` · `ESP32-CAM` · `Arduino` · `Embedded Vision`

---

## 🚗 Bachelor Thesis

### [Gesture-Controlled Robotic Car](https://github.com/ikhlaskenn/gesture-controlled-robotic-car)

A robotic vehicle driven by **hand gestures** through a wearable transmitter.

- ESP32 microcontrollers with Bluetooth communication
- IMU-based gesture recognition
- Real-time motor control via an L298N driver

`ESP32` · `IMU` · `Bluetooth` · `Embedded C`

---

## 📂 Other Projects

### [Energy Consumption Analytics and Reporting Tool](https://github.com/ikhlaskenn/energy-consumption-forecast-csharp)
A C# desktop application modelling household appliances as objects, storing consumption sessions in **SQLite**, and exporting PDF and Excel reports. Built around an abstract `Device` base class, so a new appliance is a new class and nothing else changes.

`C#` · `.NET` · `SQLite` · `iTextSharp` · `ClosedXML`

### [ASP.NET Orchard Core Web Application](https://github.com/ikhlaskenn/aspnet-orchard-core-app)
A modular web application built on **ASP.NET Core** and **Orchard Core CMS**: custom content types and modules, role-based authentication, admin dashboard configuration.

`C#` · `ASP.NET Core` · `Orchard Core`

---

## 🏭 Professional Experience

- Quality and electrical testing internship in automotive cable manufacturing — production testing, traceability, ISO 9001 context
- Automation and maintenance internship at ONCF (railways), including equipment quotations and bills of materials
- International client project management at Bio-Rad, with SAP and Salesforce

---

## 🌍 Languages

- **Arabic** — Native
- **French** — Professional
- **English** — Professional (engineering degree taught in English)

---

## 📫 Contact

- 💼 [linkedin.com/in/ikhlass-kennich](https://www.linkedin.com/in/ikhlass-kennich)
- 📧 ikhlass.kennich66@gmail.com

---

⭐ Actively maintained, with new engineering projects and technical documentation added as they are completed.
