<!-- ========================================================================= -->
<!-- DAVID RICHARDSON — GITHUB PROFILE README                                  -->
<!-- ========================================================================= -->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner_vga_dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner_vga.png">
    <img src="assets/banner_vga.png" alt="David Richardson FPGA engineering banner" style="max-width: 100%; height: auto;">
  </picture>
</p>

<h1 align="center">David Richardson</h1>

<p align="center">
  <b>Computer Engineering • FPGA/RTL Systems • Sensor Fusion • Physics-Driven Simulation</b>
</p>

<p align="center">
  Deterministic digital systems built from physical principles through instrumentation, verification, and visualization.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FPGA-Artix--7-informational" alt="FPGA Artix-7 badge">
  <img src="https://img.shields.io/badge/RTL-Verilog-blue" alt="Verilog badge">
  <img src="https://img.shields.io/badge/Language-C%2FC%2B%2B-success" alt="C/C++ badge">
  <img src="https://img.shields.io/badge/Scientific-MATLAB%20%7C%20Python-orange" alt="MATLAB Python badge">
  <img src="https://img.shields.io/badge/Workflow-Verification--First-important" alt="Verification-first badge">
  <img src="https://img.shields.io/badge/Documentation-LaTeX-9cf" alt="LaTeX badge">
</p>

---

## Overview

Engineering work centers on real-time digital systems with strong emphasis on:

- deterministic FPGA sensing and control
- explicit clock-domain crossing discipline
- telemetry and visualization pipelines
- physics-driven simulation engines
- rigorous technical documentation
- instrumentation-backed verification

<p align="center">
  <b>Closed-loop engineering workflow</b><br>
  physical model → mathematical formalism → algorithm → RTL / C / C++ → instrumentation → verification → visualization
</p>

---

## Research Interests

Research interests are centered around the design of reliable, interpretable, and resource-conscious real-time systems for sensing, visualization, and computation. Current interests include deterministic FPGA architectures, sensor-fusion pipelines, embedded scientific instrumentation, fixed-point physical modeling, clock-domain-safe visualization systems, and simulation methods that preserve physical structure while scaling computationally. These directions support internship, undergraduate research, and graduate work in digital systems, embedded hardware, scientific computing, robotics, instrumentation, and real-time sensing platforms.

---

## Current Focus

- **AquaFusion Sonar Vision System**  
  FPGA-based sonar + camera fusion with spatial mapping and HUD rendering for real-time environmental awareness.

- **Deterministic FPGA Visualization**  
  VGA/HDMI overlay systems with frame-stable rendering, explicit commit points, and CDC-safe telemetry transfer.

- **Physics-Driven Simulation**  
  Barnes–Hut gravitational engines in 2D and 3D using structured spatial hierarchies and performance-aware numerical methods.

---

## Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌊 AquaFusion_Sonar_Vision_System</h3>
      <p><b>FPGA sonar + camera fusion for real-time environmental awareness and HUD rendering</b></p>
      <p>
        Deterministic instrumentation platform integrating ultrasonic ranging, camera video,
        spatial map accumulation, and synchronized overlay rendering.
      </p>
      <p>
        <b>Focus areas:</b><br>
        sonar acquisition • OV5640/Pcam control • SYS→PIX snapshot buses • tear-free HUD compositing • observability-first debug
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/AquaFusion_Sonar_Vision_System">Repository</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ FPGA_Signal_Control_System</h3>
      <p><b>Hardware-only sensing, control, and visualization on Artix-7</b></p>
      <p>
        Real-time FPGA control laboratory built around physical-unit mapping,
        live VGA output, UART telemetry, and deterministic synchronous pipelines.
      </p>
      <p>
        <b>Highlights:</b><br>
        VGA HUD • fixed-point control • UART telemetry • PWM generation • sensor instrumentation • CDC-safe rendering
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/FPGA_Signal_Control_System">Repository</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌌 Generic_Quadtree_BarnesHut_Simulator</h3>
      <p><b>2D Barnes–Hut gravitational simulation engine</b></p>
      <p>
        Adaptive quadtree-based N-body simulation emphasizing numerical structure,
        approximation quality, and visualization.
      </p>
      <p>
        <b>Themes:</b><br>
        spatial subdivision • O(N log N) approximation • integration methods • diagnostics
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/Generic_Quadtree_BarnesHut_Simulator">Repository</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🧊 Hashed_Octree_3D_BarnesHut</h3>
      <p><b>3D Barnes–Hut engine using Morton-encoded hashed octrees</b></p>
      <p>
        3D gravitational simulation framework focused on scalable spatial indexing,
        hierarchical aggregation, and performance-oriented implementation.
      </p>
      <p>
        <b>Themes:</b><br>
        Morton codes • hashed octrees • multipole approximation • structured C++ design
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/Hashed_Octree_3D_BarnesHut">Repository</a>
      </p>
    </td>
  </tr>
</table>

---

## Engineering Areas

### FPGA / RTL Systems
- synchronous digital architecture
- CDC-safe multi-domain systems
- VGA / HDMI rendering pipelines
- UART, I2C, PWM, and sensor interfaces
- fixed-point arithmetic and physical-unit mapping

### Embedded and Low-Level Systems
- register-level peripheral reasoning
- timing-aware protocol debugging
- instrumentation-driven bring-up
- hardware/software interface discipline

### Simulation and Numerical Computing
- N-body gravitational systems
- quadtrees and octrees
- multipole approximation
- numerical stability and performance scaling

### Documentation and Reproducibility
- LaTeX technical reports
- architecture contracts and timing documentation
- verification methodology
- Tcl-based build and regeneration flows

---

## Skills and Tools

<p>
  <img src="https://img.shields.io/badge/Verilog-RTL-blueviolet" alt="Verilog badge">
  <img src="https://img.shields.io/badge/C-Systems-informational" alt="C badge">
  <img src="https://img.shields.io/badge/C%2B%2B17-Simulation-00599C" alt="C++17 badge">
  <img src="https://img.shields.io/badge/Python-Analysis-3776AB" alt="Python badge">
  <img src="https://img.shields.io/badge/MATLAB-Modeling-orange" alt="MATLAB badge">
  <img src="https://img.shields.io/badge/Tcl-Vivado%20Flows-critical" alt="Tcl badge">
  <img src="https://img.shields.io/badge/LaTeX-Documentation-008080" alt="LaTeX badge">
  <img src="https://img.shields.io/badge/Vivado-Xilinx-red" alt="Vivado badge">
</p>

---

## Selected Results

<details>
<summary><b>Expand gallery</b></summary>

### FPGA Implementation
<img src="https://github.com/user-attachments/assets/c5d7a079-df77-4224-8286-96f56844d270" width="100%"/>

### Top-Level RTL Schematic
<img src="https://github.com/user-attachments/assets/d726d9dc-9c0f-4bc3-82c3-3efed9e8fda4" width="100%"/>

### Bench Setup
<img src="https://github.com/user-attachments/assets/13c20e2c-417c-4870-bf42-34b2b5f2e4ed" width="100%"/>

### MATLAB Telemetry and Modeling
<img src="https://github.com/user-attachments/assets/02e8776b-5178-493b-b479-c464a6d8c6e0" width="100%"/>

### Real-Time HUD Output
<img src="https://github.com/user-attachments/assets/f93a67c1-1c55-498d-ba6d-71f74f197d44" width="100%"/>

</details>

---

## Featured Report

A major part of this portfolio is not only implementation, but rigorous engineering explanation.

Representative documentation themes include:

- physical motivation
- mathematical formulation
- interface and timing contracts
- CDC doctrine
- verification methodology
- instrumentation-backed hardware validation

**Featured PDF**  
[Sonar_Fusion_Signal_CAT_Thesis (3).pdf](https://github.com/user-attachments/files/24847481/Sonar_Fusion_Signal_CAT_Thesis.3.pdf)

---

## GitHub Activity (Signal-Only)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DavidRichardson02&show_icons=true&hide_title=true&hide_rank=true&count_private=true&include_all_commits=true&disable_animations=true" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavidRichardson02&layout=compact&hide_title=true&langs_count=6&disable_animations=true" height="140"/>
</p>

---

## Contact

- LinkedIn: `linkedin.com/in/david-richardson-0099281b6`
- Email: `02richardsondavid@gmail.com`
- Portfolio: `davidrichardson02.github.io`
- Resume: [Resumë (9).pdf](https://github.com/user-attachments/files/24847510/Resume.9.pdf)

---

<p align="center">
  <b>Structured. Deterministic. Physics-driven engineering from first principles.</b>
</p>
