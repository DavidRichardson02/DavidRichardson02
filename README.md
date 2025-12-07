<p align="center">
  <img src="assets/banner_vga.png" width="100%" alt="FPGA Banner">
</p>

<h1 align="center">David Richardson</h1>
<h3 align="center">Computer Engineering • FPGA/RTL Systems • Physics-Driven Simulation • Automated Data Analysis</h3>

I like taking ideas from first principles and building systems around them from the ground up — **physical theory → mathematical models → algorithms → RTL/C/C++/assembly → instrumentation tools → analysis and visualization**.  
My work takes place predominantly at the intersection of **physics, mathematics, and computation** — and spans **real-time FPGA sensing and control systems**, **high-performance numerical simulation engines**, and **robust C data analysis+modeling pipelines**, unified by a focus on correctness, timing, structured dataflow, rigorous documentation, and deep technical understanding.


---

## 🔭 Current Focus

- **FPGA Signal Control System** – Nexys A7 physics control lab with ToF mapping, VGA HUD, UART telemetry, PWM fan control, PIR sensing, and rotary-encoder surveying.  
- **Barnes–Hut N-Body Simulations (2D & 3D)** – C++17 engines using quadtrees and hashed-octrees with Morton ordering for scalable gravitational dynamics.  
- **Automated CSV Analysis Pipeline** – C framework for dataset standardization, modeling, and diagnostics for scientific/engineering logs.

---



# 🚀 Featured Work

## **FPGA_Signal_Control_System**  
*A hardware-only sensing & control laboratory running entirely on an Artix-7 FPGA.*

- Real-time **Time-of-Flight distance mapping**
- **VGA HUD engine** with framebuffer range plots and status overlays  
- **Temperature telemetry → PWM fan control** (Q1.15 fixed-point)  
- **PIR-based occupancy sensing**  
- **Rotary encoder** driven manual/automatic surveying  
- **Structured UART telemetry** (timestamp, θ, distance, temp, duty, CRC)  
- Clean **CDC boundaries**, ready/valid datapaths, disciplined module partitioning  

<p align="center">
  <img src="assets/VGA_Output.jpeg" width="75%">
</p>

---

## **Barnes–Hut Simulation Engines (2D & 3D)**  
*High-performance gravitational modeling using quadtrees, hashed-octrees, and Morton-ordered spatial hierarchies.*

Designed from mathematical first principles and optimized for:
- **Adaptive spatial resolution**
- **O(N log N)** force evaluation
- **Interactive visualization**
- **Stable symplectic integration**

### **Quadtree Engine (2D)**  
<p align="center">
  <img src="assets/quadtree.png" width="90%">
</p>

### **Octree Engine (3D)**  
<p align="center">
  <img src="assets/octree_bounds_visual.png" width="90%">
</p>

### **Simulation Gallery**
<p align="center">
  <img width="1508" height="1023" alt="Screenshot 2024-02-21 at 2 56 35 AM" src="https://github.com/user-attachments/assets/90a1477a-d7aa-4386-af1c-89f0ee0f7520" />
<img width="2056" height="1329" alt="Screenshot 2025-09-17 at 12 04 30 PM" src="https://github.com/user-attachments/assets/baecf4a8-8363-4fc3-b17f-f81f8c22e05d" />
<img width="2056" height="1329" alt="Screenshot 2025-09-17 at 11 56 53 AM" src="https://github.com/user-attachments/assets/91b11055-866c-4725-99e0-c761dc9b5630" />

</p>

These engines power **galaxy simulations**, **energy-tracked N-body systems**, and **interactive exploration tools**.

---

# 🧠 Technical Focus Areas

### **Digital / FPGA Engineering**
- RTL architecture (FSMs, I²C, UART, PWM, XADC front-ends)  
- VGA graphics engines, HUD overlays, BRAM-backed framebuffers  
- CDC-safe design across 25 MHz ⇄ 100 MHz domains  
- Q-format fixed-point modeling (Q1.15) unified across HDL, MATLAB, and C++  
- Hardware-in-the-loop validation: logic analyzer, DMM, AD2 scope, UART decoders  

### **High-Performance C++**
- Quadtree / octree spatial partitioning  
- Barnes–Hut gravitational solvers  
- Morton (Z-order) indexing & cache-friendly data layouts  
- Symplectic integrators (leapfrog / velocity Verlet)  
- Real-time visualization & tooling (OpenFrameworks, custom UIs)  

### **Mathematical Modeling & Analysis (MATLAB / C / Python)**
- Telemetry decoders (framing, CRC verification)  
- 1D diffusion models (explicit / implicit schemes)  
- Stability surfaces & parametric sweeps  
- Real-time polar plots, 2D/3D signal visualization  
- Image streaming pipelines for FPGA framebuffers  

---

# 📦 Highlighted Repositories

### **FPGA_Signal_Control_System**  
Integrated real-time sensor suite, VGA HUD, temperature control, and telemetry running on an Artix-7 FPGA.

### **Generic_Quadtree_BarnesHut_Simulator**  
2D gravitational engine with adaptive quadtree refinement, energy visualization, and interactive tooling.

### **Hashed_Octree_3D_BarnesHut**  
3D N-body simulation using Morton-encoded hashed octrees for highly scalable spatial subdivision.

### **Automated_CSV_Data_Analysis**  
C pipeline for structured dataset modeling, transformations, and scientific diagnostics.

---

# 🧰 Skills & Tools
### **Hardware, RTL & Mixed-Signal Engineering**
![Verilog](https://img.shields.io/badge/HDL-Verilog-2b8?style=for-the-badge)
![FPGA](https://img.shields.io/badge/FPGA-Artix7-025?style=for-the-badge&logo=xilinx)
![Vivado](https://img.shields.io/badge/Vivado-2023.2-28a?style=for-the-badge&logo=xilinx)
![I2C](https://img.shields.io/badge/I²C-Sensor_Interface-444?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-2Mbit%2Fs-orange?style=for-the-badge)
![PWM](https://img.shields.io/badge/PWM-Actuator_Control-red?style=for-the-badge)
![XADC](https://img.shields.io/badge/XADC-Mixed_Signal-yellow?style=for-the-badge)

### **Scientific Computing, Modeling & Simulation**
![C++](https://img.shields.io/badge/C++17-High_Performance-00599C?style=for-the-badge&logo=cplusplus)
![OpenFrameworks](https://img.shields.io/badge/OpenFrameworks-Visualization-1b1?style=for-the-badge)
![MATLAB](https://img.shields.io/badge/MATLAB-Numerical_Modeling-orange?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Scientific_Tooling-blue?style=for-the-badge&logo=python)
![Eigen](https://img.shields.io/badge/Eigen-Linear_Algebra-lightgrey?style=for-the-badge)
![FFTW](https://img.shields.io/badge/FFTW-Spectral_Methods-purple?style=for-the-badge)

### **Algorithmic & Mathematical Tooling**
- Spatial data structures (quadtrees, octrees, hashed/oct Morton layouts)  
- N-body solvers, multipole approximations, gravitational kernels  
- Diffusion PDEs, stability surfaces, fixed-point pipelines  
- Symplectic integrators, numerical conditioning, error analysis  

### **Workflow & Engineering Infrastructure**
![Git](https://img.shields.io/badge/Git-Version_Control-black?style=for-the-badge&logo=git)
![Linux](https://img.shields.io/badge/Linux-Dev_Environment-important?style=for-the-badge&logo=linux)
![CMake](https://img.shields.io/badge/CMake-Build_System-064F8C?style=for-the-badge&logo=cmake)
![WaveForms](https://img.shields.io/badge/WaveForms-HIL_Testing-1f5?style=for-the-badge)
![MATLAB_TBX](https://img.shields.io/badge/MATLAB-Telemetry_Toolbox-orange?style=for-the-badge)

---















## 🖼️ Project Gallery
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

