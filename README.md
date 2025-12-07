<!-- ============================================================
   DARK/LIGHT MODE ADAPTIVE BANNER (RESPONSIVE)
   ============================================================ -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner_vga_dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner_vga.png">
    <img src="assets/banner_vga.png" alt="FPGA Banner" style="max-width: 100%; height: auto;">
  </picture>
</p>

<h1 align="center">David Richardson</h1>
<h3 align="center">Computer Engineering • FPGA/RTL Systems • Physics-Driven Simulation • Automated Data Analysis</h3>

<!-- ============================================================
   ANIMATED SVG ORBIT VISUALIZER (NO JS, GITHUB-SAFE)
   ============================================================ -->
<p align="center">
  <svg width="260" height="80" viewBox="0 0 260 80" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad-orbit" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#2dd4ff" />
        <stop offset="100%" stop-color="#facc15" />
      </linearGradient>
    </defs>

    <!-- Central "FPGA" node -->
    <rect x="95" y="22" rx="6" ry="6" width="70" height="36" fill="#111827" stroke="url(#grad-orbit)" stroke-width="1.4" />
    <text x="130" y="44" text-anchor="middle" font-size="11" fill="#e5e7eb" font-family="system-ui, -apple-system, BlinkMacSystemFont, sans-serif">
      physics → RTL
    </text>

    <!-- Orbit path -->
    <ellipse cx="130" cy="40" rx="110" ry="28" fill="none" stroke="rgba(148,163,184,0.4)" stroke-width="1" stroke-dasharray="4 6" />

    <!-- Orbiting node (animated) -->
    <circle id="orbiter" cx="240" cy="40" r="4" fill="#facc15">
      <animateMotion
        dur="7s"
        repeatCount="indefinite"
        path="M 20,40 A 110,28 0 1 1 240,40 A 110,28 0 1 1 20,40"
      />
    </circle>

    <!-- Labels -->
    <text x="35" y="20" text-anchor="middle" font-size="9" fill="#9ca3af" font-family="system-ui, -apple-system, BlinkMacSystemFont, sans-serif">
      math models
    </text>
    <text x="225" y="66" text-anchor="middle" font-size="9" fill="#9ca3af" font-family="system-ui, -apple-system, BlinkMacSystemFont, sans-serif">
      analysis &amp; visualization
    </text>
  </svg>
</p>

<p align="center">
  <b>Structured. Physics-driven. Bottom-up engineering.</b>
</p>

I like taking ideas from first principles and building systems around them from the ground up — **physical theory → mathematical models → algorithms → RTL/C/C++/assembly → instrumentation tools → analysis and visualization**.  
My work takes place predominantly at the intersection of **physics, mathematics, and computation** — and spans **real-time FPGA sensing and control systems**, **high-performance numerical simulation engines**, and **robust C data analysis+modeling pipelines**, unified by a focus on correctness, timing, structured dataflow, rigorous documentation, and deep technical understanding.

---

# 🧭 Navigation

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
   - [Language → Project Mapping](#language--project-mapping)  
5. [Highlighted Repositories](#highlighted-repositories)  

---

# 🔍 Overview

A snapshot of the systems I like to build:

- Real-time FPGA sensor fusion and mixed-signal control  
- High-performance N-body gravitational simulation (2D & 3D)  
- Telemetry pipelines from UART/FPGA → MATLAB/Python → visualization  
- Deeply documented engineering flows (RTL, C/C++, math, LaTeX)

My engineering approach is bottom-up and physics-aware: start from the system model, formalize it mathematically, then carry it all the way through algorithms, code, hardware, verification, and visualization.

---

# 🏗️ Architecture & Featured Work

## <a name="fpga_signal_control_system"></a>⚡ FPGA_Signal_Control_System (Artix-7)

*A hardware-only physics control laboratory with live visualization.*

- Real-time **Time-of-Flight distance mapping**  
- **VGA HUD** with framebuffer plots and status widgets  
- **Temperature telemetry → PWM fan control** (Q1.15 fixed-point)  
- **PIR-based occupancy sensing**  
- **Rotary encoder**-driven manual and automatic surveying modes  
- **Structured UART telemetry** (timestamp, θ, distance, temp, duty, CRC)  
- Clean **CDC boundaries**, ready/valid datapaths, disciplined module partitioning  

<p align="center">
  <img src="assets/VGA_Output.jpeg" alt="VGA Output" style="max-width: 75%; height: auto;">
</p>

---

## <a name="barnes–hut-simulation-engines"></a>🌌 Barnes–Hut Simulation Engines (2D & 3D)

High-performance gravitational modeling built around:

- Adaptive quadtrees & Morton-encoded hashed octrees  
- O(N log N) multipole approximations  
- Stable symplectic integration (leapfrog, velocity Verlet)  
- Real-time visualization, energy tracking, and parameter exploration  

<p align="center">
  <img src="assets/quadtree.png" alt="Quadtree" style="max-width: 90%; height: auto;">
  <img src="assets/octree_bounds_visual.png" alt="Octree Bounds" style="max-width: 90%; height: auto;">
</p>

---

# 🎛️ Results & Project Gallery

<details>
<summary><b>Click to expand project visuals</b></summary><br>

### FPGA Vivado Implementation
<img src="https://github.com/user-attachments/assets/c5d7a079-df77-4224-8286-96f56844d270" alt="Device Implementation" style="max-width: 100%; height: auto;">

### Top-Level RTL Schematic
<img src="https://github.com/user-attachments/assets/d726d9dc-9c0f-4bc3-82c3-3efed9e8fda4" alt="RTL Schematic" style="max-width: 100%; height: auto;">

### Hardware Bench Setup
<img src="https://github.com/user-attachments/assets/13c20e2c-417c-4870-bf42-34b2b5f2e4ed" alt="Hardware Bench" style="max-width: 100%; height: auto;">

### MATLAB Telemetry + Vivado View
<img src="https://github.com/user-attachments/assets/02e8776b-5178-493b-b479-c464a6d8c6e0" alt="MATLAB Models 1" style="max-width: 100%; height: auto;">
<img src="https://github.com/user-attachments/assets/973b8193-e1a7-4f96-be91-c27db3f349ad" alt="MATLAB Models 2" style="max-width: 100%; height: auto;">

### Showcase Setup
<img src="https://github.com/user-attachments/assets/62af5527-ce3a-4a05-82eb-2ae0886e089f" alt="Showcase Setup" style="max-width: 100%; height: auto;">

### VGA Real-Time HUD Output
<img src="https://github.com/user-attachments/assets/f93a67c1-1c55-498d-ba6d-71f74f197d44" alt="VGA HUD" style="max-width: 100%; height: auto;">

</details>

---

# 🧰 Languages & Technical Ecosystem

This combines badges, short descriptions, and direct mapping to projects.

---

## 🔤 Badges

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

## 📚 Ecosystem Summary

### Programming & HDL
- 💠 **C** — embedded utilities, telemetry decoders, dataset tools  
- 💠 **C++17** — Barnes–Hut engines, Morton-ordered spatial structures  
- 🔧 **Verilog RTL** — VGA pipelines, UART/I²C/PWM, XADC front-ends, fixed-point logic  
- 🧩 **Assembly (HCS12 / ARM)** — register-level microcontroller work  

### Scientific Computing
- 📐 **MATLAB** — numerical modeling, telemetry analysis, real-time plotting  
- 🐍 **Python** — scripts, CSV ingestion, visualization helpers  

### Documentation & Build Infrastructure
- ✍️ **LaTeX** — engineering reports, posters, derivations  
- 🔗 **Markdown** — GitHub docs & READMEs  
- 🛠️ **Tcl** — Vivado non-project builds, automated regeneration  

---

## 🧬 Language → Project Mapping

| Language | FPGA_Signal_Control_System | N-Body Barnes–Hut Engines | CSV Analysis Pipeline | MCU / Embedded Work | Documentation |
|---------|-----------------------------|---------------------------|-----------------------|----------------------|--------------|
| **C** | UART log decoders, MATLAB bridge, tools | — | Dataset modeling, parsers | Sensor utilities | — |
| **C++17** | Host-side visualizers | Full Barnes–Hut engines, Morton grids | — | — | — |
| **Verilog RTL** | VGA engine, HUD overlay, I²C, UART, PWM, XADC | — | — | — | — |
| **Assembly** | — | — | — | HCS12/ARM register-level labs & drivers | — |
| **MATLAB** | Telemetry decoding, range plots | Stability & energy sweeps | — | — | Figures & analysis |
| **Python** | CSV ingestion, log tooling | Visualization helpers | Automation scripts | — | — |
| **LaTeX** | FPGA project reports | Simulation write-ups | Data pipeline theory | Coursework | — |
| **Tcl** | Vivado automation, project regeneration | — | — | — | Build scripts |
| **Markdown** | Repo docs, root README | Repo docs | Data documentation | — | All repos |

---

# 📦 Highlighted Repositories

<details>
<summary><b>Click to expand repository summaries</b></summary><br>

### FPGA_Signal_Control_System  
Integrated FPGA sensing/control system with ToF mapping, VGA HUD, mixed-signal telemetry, and fan/PIR/rotary control.

### Generic_Quadtree_BarnesHut_Simulator  
2D gravitational engine with adaptive quadtree refinement and interactive visualization.

### Hashed_Octree_3D_BarnesHut  
3D N-body simulation using Morton-encoded hashed octrees for scalable spatial subdivision.

### Automated_CSV_Data_Analysis  
C pipeline for structured dataset modeling, transformations, and diagnostics.

</details>

---
