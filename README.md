# 👋 Hi, I'm David Richardson  

Computer Engineering student building systems at the intersection of **physics, mathematics, and computation** — from FPGA-based real-time sensing and control to high-performance C++ simulation engines and data analysis pipelines.

I like taking ideas from first principles all the way to hardware and tools:  
**theory → models → algorithms → RTL → instrumentation → analysis**.  
My work emphasizes correctness, timing, structured dataflow, and rigorous documentation.

---

## 🔭 Current Focus

- **FPGA Signal Control System** – Nexys A7 physics control lab with ToF mapping, VGA HUD, UART telemetry, PWM fan control, PIR sensing, and rotary-encoder surveying.  
- **Barnes–Hut N-Body Simulations (2D & 3D)** – C++17 engines using quadtrees and hashed-octrees with Morton ordering for scalable gravitational dynamics.  
- **Automated CSV Analysis Pipeline** – C++17 framework for dataset standardization, modeling, and diagnostics for scientific/engineering logs.

---

## 🚀 Featured Project — FPGA_Signal_Control_System  

A mixed-signal real-time measurement and control platform built entirely in hardware on a **Nexys A7-100T (Artix-7)**.

**What it does**

- **2D spatial mapping** using a Pmod **Time-of-Flight (ISL29501)** sensor swept over angle  
- **Temperature telemetry → PWM fan control** with hysteresis and occupancy extensions  
- **PIR motion sensing** with temporal decay logic  
- **Rotary encoder–driven surveying** and HUD interaction  
- **Structured UART telemetry** (timestamp, θ_q15, dist_mm, temperature, duty, status, CRC)  
- **Full 640×480 VGA pipeline**:
  - ToF range plot with framebuffer + rings/axes  
  - Right-side HUD (temperature bar, fan tiles, PIR, UART counters, angle indicators)  
  - Double-buffered logo/image viewport streamed over UART  

**How it’s built**

- Single 100 MHz fabric clock, with tick-enable–based slow behavior  
- Q1.15 fixed-point numerics shared between RTL, MATLAB, and C++ tools  
- CDC-safe bridges to a 25 MHz pixel clock domain  
- Ready/valid streaming between ToF sensor, packetizer, UART TX/RX, and video/telemetry paths  

(Full theory-of-operation, cheat sheet, and poster live in the project repo and portfolio.)

---

## 🧠 Technical Focus Areas

### Digital / FPGA & Embedded

- Verilog RTL: FSMs, I²C, UART, PWM, XADC front-ends, CDC synchronization  
- VGA timing cores, HUD engines, framebuffer pipelines, and logo/overlay modules  
- Q-format fixed-point modeling (Q1.15) for temperature, angle, duty, and scaling  
- Nexys A7 (Artix-7), HCS12, ARM Cortex-M, UART/I²C/SPI, mixed-signal bench work

### High-Performance C/C++ & Numerical Modeling

- Barnes–Hut kernels, quadtrees, hashed-octrees, Morton ordering  
- Numerical integration and stability-aware simulation loops  
- CSV analytics frameworks (schema inference, transformation, modeling)  
- Tooling and libraries: modern C++17, Eigen/FFTW/OpenMP where appropriate

### Tooling & Workflow

- Vivado Design Suite, WaveForms, MATLAB/Simulink  
- Git/GitHub, CMake/Ninja, CI, cross-platform dev on macOS, Linux, and Windows  

---

## 📦 Selected Repositories

- **FPGA_Signal_Control_System** – Integrated ToF mapping, temperature-based fan control, PIR sensing, rotary surveying, UART telemetry, and VGA HUD on an Artix-7 FPGA.  
- **Generic_Quadtree_BarnesHut_Simulator** – 2D interactive N-body engine with adaptive quadtree partitioning and Barnes–Hut approximation.  
- **Hashed_Octree_3D_BarnesHut** – 3D N-body framework using Morton-ordered hashed octrees for cache-friendly force evaluation.  
- **Automated_CSV_Data_Analysis** – Modular C++17 pipeline for CSV standardization, integrity checks, and statistical modeling across large datasets.  
- **OpenFrameworks_UI_Library** – Lightweight UI layer for visualization tools and simulation control panels.  

---

## 🖼️ Project Gallery
```markdown

### FPGA Implemented Design (Vivado)
<img width="600" height="833" alt="device" src="https://github.com/user-attachments/assets/c5d7a079-df77-4224-8286-96f56844d270" />


### Top-Level RTL Schematic
<img width="1600" height="900" alt="FPGA_Schematic_Minimized" src="https://github.com/user-attachments/assets/d726d9dc-9c0f-4bc3-82c3-3efed9e8fda4" />


### Hardware Bench Setup
![FPGA_Project_Hardware](https://github.com/user-attachments/assets/13c20e2c-417c-4870-bf42-34b2b5f2e4ed)


### MATLAB Telemetry + Vivado View
<img width="2054" height="1217" alt="MATLAB_Models1" src="https://github.com/user-attachments/assets/02e8776b-5178-493b-b479-c464a6d8c6e0" />
<img width="2056" height="1329" alt="MATLAB_Models2" src="https://github.com/user-attachments/assets/973b8193-e1a7-4f96-be91-c27db3f349ad" />


### Competition / Showcase Setup
![Project_Showcase](https://github.com/user-attachments/assets/62af5527-ce3a-4a05-82eb-2ae0886e089f)


### VGA Real-Time HUD Output
![VGA_Output](https://github.com/user-attachments/assets/f93a67c1-1c55-498d-ba6d-71f74f197d44)

