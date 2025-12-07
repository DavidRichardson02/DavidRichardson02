# 👋 Hi, I'm David Richardson  
Computer Engineering student specializing in **FPGA/RTL design**, **embedded systems**, and **high-performance C/C++**.

I build systems from first principles — physics → math → algorithms → RTL → instrumentation.  
My work emphasizes correctness, timing, structured dataflow, and high-quality engineering documentation.

---

## 🚀 Featured Project — FPGA_Signal_Control_System  
A mixed-signal real-time sensing, control, and visualization platform built entirely in hardware on a **Nexys A7-100T (Artix-7)** FPGA.

### What it does
- **2D spatial mapping** using a Pmod **Time-of-Flight (ISL29501)** sensor swept over angle  
- **Temperature monitoring** via XADC → **PWM fan control** with hysteresis  
- **PIR-based occupancy detection**  
- **Rotary encoder**–driven surveying and interaction  
- **Structured UART telemetry** (timestamp, θ_q15, dist_mm, temperature, duty, CRC)  
- **Full 640×480 VGA visualization pipeline**:  
  - ToF range plot  
  - HUD panel (temperature, duty, fan logic, PIR, UART counters, angle widgets)  
  - Double-buffered image/logo viewport streamed via UART  

This system is fully synchronous (100 MHz), with clean CDC boundaries, fixed-point Q1.15 numerics, and ready/valid streaming between all major modules.  
A complete architecture description is documented in my project report and cheat sheet.  
:contentReference[oaicite:0]{index=0}  
:contentReference[oaicite:1]{index=1}  
:contentReference[oaicite:2]{index=2}

---

## 🛠️ Technical Focus Areas

### **Digital / FPGA Engineering**
- Verilog RTL: FSMs, I²C, UART, PWM, XADC front-ends, CDC synchronization  
- VGA graphics engines (timing cores, colorizers, HUD overlays, framebuffer pipelines)  
- Q1.15 fixed-point design for angles, temperature, and duty cycles  
- Vivado: XDC constraints, Tcl automation, block-RAM architectures, implementation debugging  

### **Embedded / Mixed-Signal Systems**
- Time-of-Flight ranging (ISL29501)  
- PIR motion sensing and temporal decay filters  
- Closed-loop cooling control with occupancy-aware logic  
- Rotary encoders, servos, and surveying FSMs  
- MATLAB telemetry pipelines, decoders, and live plotting

### **High-Performance C/C++ & Modeling**
- Spatial data structures (quadtrees, hashed-octrees, Morton ordering)  
- Barnes-Hut N-body simulations (2D + 3D)  
- Modular CSV parsing / analysis frameworks  
- Numerics, physics-informed modeling, and algorithm optimization

---

## 📦 Highlighted Repositories
- **FPGA_Signal_Control_System** — integrated spatial mapping, telemetry, cooling control, and VGA visualization  
- **Automated_CSV_Data_Analysis** — modular C++ data-processing and modeling pipeline  
- **Barnes-Hut-Simulators** — real-time gravitational engines with spatial hierarchies  
- **MATLAB Telemetry Toolkit** — UART decoder + live polar plotting + CSV logging

---

## 🖼️ Project Gallery (Selected Images)
*(Add these as markdown images once pushed to your repo resources folder)*

- FPGA implemented design (Vivado device view)  
- RTL top-level schematic  
- Full hardware bench setup with AD2 instrumentation  
- MATLAB telemetry plots  
- VGA HUD output and live ToF range map  
- Engineering poster from project presentation

---

## 📫 Contact
- **LinkedIn:** https://www.linkedin.com/in/david-richardson-0099281b6/  
- **Portfolio:** https://davidrichardson02.github.io/  
- **Email:** 02richardsondavid@gmail.com  

