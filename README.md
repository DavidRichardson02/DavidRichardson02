<!-- ============================================================
   DARK/LIGHT MODE ADAPTIVE BANNER
   GitHub automatically swaps based on theme preference.
   ============================================================ -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner_vga_dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner_vga.png">
    <img src="assets/banner_vga.png" width="100%" alt="FPGA Banner">
  </picture>
</p>

<h1 align="center">David Richardson</h1>
<h3 align="center">Computer Engineering • FPGA/RTL Systems • Physics-Driven Simulation • Automated Data Analysis</h3>

<p align="center">
  <b>Structured. Physics-driven. Bottom-up engineering.</b>
</p>

I like taking ideas from first principles and building systems around them from the ground up — **physical theory → mathematical models → algorithms → RTL/C/C++/assembly → instrumentation tools → analysis and visualization**.  
My work takes place predominantly at the intersection of **physics, mathematics, and computation** — and spans **real-time FPGA sensing and control systems**, **high-performance numerical simulation engines**, and **robust C data analysis+modeling pipelines**, unified by a focus on correctness, timing, structured dataflow, rigorous documentation, and deep technical understanding.

---

# 🧭 Navigation Sidebar

<p align="center">
  <a href="#overview">Overview</a> • 
  <a href="#architecture--featured-work">Architecture & Featured Work</a> • 
  <a href="#results--project-gallery">Results</a> • 
  <a href="#languages--technical-ecosystem">Languages & Technical Ecosystem</a> • 
  <a href="#highlighted-repositories">Repositories</a>
</p>

---

# 📑 Table of Contents

1. [Overview](#overview)  
2. [Architecture & Featured Work](#architecture--featured-work)  
   - [FPGA Signal Control System](#fpga_signal_control_system)  
   - [Barnes–Hut Simulation Engines](#barnes–hut-simulation-engines)  
3. [Results & Project Gallery](#results--project-gallery)  
4. [Languages & Technical Ecosystem](#languages--technical-ecosystem)  
   - [Badges](#badges)  
   - [Ecosystem Summary](#ecosystem-summary)  
   - [Language → Project Matrix](#language--project-mapping)  
5. [Highlighted Repositories](#highlighted-repositories)

---

# 🔍 **Overview**

A brief snapshot of the systems I build:

- Real-time FPGA sensor fusion and mixed-signal systems  
- High-performance N-body gravitational solvers (2D/3D)  
- Structured scientific telemetry pipelines (C / MATLAB / Python)  
- Full-stack engineering documentation, diagrams, and modeling  

My engineering philosophy emphasizes **bottom-up rigor**, explicit timing models, numerical stability, and strong modularity across hardware and software.

---

# 🏗️ **Architecture & Featured Work**

## <a name="fpga_signal_control_system"></a>⚡ **FPGA Signal Control System (Artix-7)**  
*A hardware-only real-time physics control laboratory*

- Live **ToF distance mapping**  
- **VGA HUD** overlay engine (framebuffer + telemetry widgets)  
- **Temperature → PWM fan control** (Q1.15 fixed-point)  
- **PIR-based occupancy detection**  
- **Rotary encoder surveying** (manual + automatic sweep modes)  
- **Structured UART telemetry** (timestamp, θ, distance, temp, duty, CRC)  
- Clean **CDC boundaries** and ready/valid datapaths  

<p align="center">
  <img src="assets/VGA_Output.jpeg" width="75%">
</p>

---

## <a name="barnes–hut-simulation-engines"></a>🌌 **Barnes–Hut Simulation Engines (2D & 3D)**

High-performance gravitational solvers with:

- Adaptive quadtrees & hashed-octrees  
- Morton Z-order indexing  
- O(N log N) multipole approximation  
- Symplectic integration (leapfrog, velocity Verlet)  
- Real-time visualization & energy tracking  

<p align="center">
  <img src="assets/quadtree.png" width="90%">
  <img src="assets/octree_bounds_visual.png" width="90%">
</p>

---

# 🖼️ **Results & Project Gallery**

<details>
<summary><b>Click to expand project visualizations</b></summary><br>

### FPGA Vivado Implementation  
<img width="600" src="https://github.com/user-attachments/assets/c5d7a079-df77-4224-8286-96f56844d270">

### Top-Level RTL Schematic  
<img width="1600" src="https://github.com/user-attachments/assets/d726d9dc-9c0f-4bc3-82c3-3efed9e8fda4">

### Hardware Bench Setup  
<img src="https://github.com/user-attachments/assets/13c20e2c-417c-4870-bf42-34b2b5f2e4ed">

### MATLAB Telemetry Models  
<img width="2054" src="https://github.com/user-attachments/assets/02e8776b-5178-493b-b479-c464a6d8c6e0">
<img width="2056" src="https://github.com/user-attachments/assets/973b8193-e1a7-4f96-be91-c27db3f349ad">

### Showcase Setup  
<img src="https://github.com/user-attachments/assets/62af5527-ce3a-4a05-82eb-2ae0886e089f">

### VGA HUD Output  
<img src="https://github.com/user-attachments/assets/f93a67c1-1c55-498d-ba6d-71f74f197d44">

</details>

---

# 🧰 **Languages & Technical Ecosystem**

This section integrates badges, descriptive summaries, and a full project mapping matrix.

---

## 🔤 **Badges**

![C](https://img.shields.io/badge/C-Systems_Programming-00599C?style=for-the-badge&logo=c)
![C++](https://img.shields.io/badge/C++17-High_Performance-00599C?style=for-the-badge&logo=cplusplus)
![Verilog](https://img.shields.io/badge/Verilog-RTL_Design-2b8?style=for-the-badge)
![Assembly](https://img.shields.io/badge/Assembly-HCS12_/_ARM-6e4?style=for-the-badge)
![MATLAB](https://img.shields.io/badge/MATLAB-Numerical_Modeling-orange?style=for-the-badge&logo=matlab)
![Python](https://img.shields.io/badge/Python-Scientific_Tooling-blue?style=for-the-badge&logo=python)
![LaTeX](https://img.shields.io/badge/LaTeX-Documentation-008080?style=for-the-badge&logo=latex)
![Tcl](https://img.shields.io/badge/Tcl-Vivado_Automation-424242?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Markdown-Documentation-000000?style=for-the-badge&logo=markdown)

---

## 📚 **Ecosystem Summary**

### Programming & HDL  
- 💠 **C** — embedded utilities, data parsers, telemetry decoders  
- 💠 **C++17** — N-body engines, performance-optimized math, Morton layouts  
- 🔧 **Verilog** — VGA engines, UART/I²C/PWM logic, fixed-point telemetry  
- 🧩 **Assembly** — MCU register-level interaction  

### Scientific Computing  
- 📐 **MATLAB** — modeling, real-time telemetry pipelines  
- 🐍 **Python** — scripting, data automation  

### Documentation & Build Infrastructure  
- ✍️ **LaTeX** — engineering reports  
- 🔗 **Markdown** — GitHub docs  
- 🛠️ **Tcl** — Vivado non-project flows  

---

## 🧬 **Language → Project Mapping**

| Language | FPGA System | Barnes–Hut Engines | CSV Pipeline | Embedded Work | Documentation |
|---------|-------------|-------------------|--------------|----------------|--------------|
| **C** | Telemetry decoders, tools | — | Dataset modeling, parsers | Sensor utilities | — |
| **C++17** | Host visualizers | Full engines | — | — | — |
| **Verilog** | VGA, HUD, I²C, UART, PWM | — | — | — | — |
| **Assembly** | — | — | — | HCS12/ARM drivers | — |
| **MATLAB** | Telemetry modeling | Stability sweeps | — | — | Figures |
| **Python** | CSV ingestion | Visualization | Automation | — | — |
| **LaTeX** | Reports/posters | Write-ups | Data theory | Coursework | — |
| **Tcl** | Build automation | — | — | — | Build scripts |
| **Markdown** | Repo docs | Repo docs | Data explanations | — | All repos |

---

# 📦 **Highlighted Repositories**

<details>
<summary><b>Click to expand repository summaries</b></summary><br>

### **FPGA_Signal_Control_System**  
Real-time physics control system on Artix-7 featuring ToF mapping, VGA HUD, telemetry, and mixed-signal control.

### **Generic_Quadtree_BarnesHut_Simulator**  
2D gravitational N-body solver with adaptive quadtree refinement.

### **Hashed_Octree_3D_BarnesHut**  
Scalable 3D solver using Morton-encoded hashed octrees.

### **Automated_CSV_Data_Analysis**  
C-based dataset modeling and diagnostics framework.

</details>

---
