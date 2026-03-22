<!-- ========================================================================= -->
<!-- DAVID RICHARDSON — GITHUB PROFILE README                                  -->
<!-- GRADUATE RESEARCH–ORIENTED VARIANT                                        -->
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
  <b>Computer Engineering Undergraduate • FPGA Systems • Real-Time Instrumentation • Physics-Driven Computing</b>
</p>

<p align="center">
  Research-focused engineering in deterministic digital systems, embedded instrumentation, sensor fusion, and computational modeling.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Research-FPGA%20Systems-informational" alt="FPGA systems badge">
  <img src="https://img.shields.io/badge/Focus-Real--Time%20Instrumentation-blue" alt="Real-time instrumentation badge">
  <img src="https://img.shields.io/badge/Methods-Verilog%20%7C%20C%2B%2B-success" alt="Verilog and C++ badge">
  <img src="https://img.shields.io/badge/Modeling-MATLAB%20%7C%20Python-orange" alt="MATLAB and Python badge">
  <img src="https://img.shields.io/badge/Approach-Verification--First-important" alt="Verification-first badge">
  <img src="https://img.shields.io/badge/Writing-LaTeX-9cf" alt="LaTeX badge">
</p>

---

## About

Academic and engineering work is centered on the study of real-time digital systems that must remain structured, interpretable, and physically grounded under implementation constraints. A recurring theme across projects is the translation of physical sensing problems into mathematically explicit, computationally efficient, and hardware-realizable pipelines.

Current work emphasizes:

- deterministic FPGA architectures
- real-time telemetry and visualization
- multi-sensor data acquisition and fusion
- explicit clock-domain crossing discipline
- fixed-point and resource-aware implementation
- physics-based simulation and spatial data structures
- rigorous documentation and verification methodology

<p align="center">
  <b>Research workflow</b><br>
  physical system → mathematical model → algorithmic structure → hardware/software realization → instrumentation → verification → analysis
</p>

---

## Research Interests

Research interests include real-time digital systems, FPGA-based instrumentation, sensor-fusion architectures, embedded scientific measurement platforms, fixed-point numerical methods, and physics-informed computational design. Particular interest lies in systems where correctness depends not only on functional behavior, but also on timing discipline, synchronization boundaries, data validity semantics, and interpretable visualization of internal state.

Ongoing technical themes include deterministic rendering pipelines, telemetry publication contracts, low-level sensor interfacing, resource-conscious embedded computation, and structured simulation methods such as Barnes–Hut spatial hierarchy techniques. These interests align broadly with graduate study and research in digital systems, embedded hardware, cyber-physical systems, scientific computing, sensing and perception, robotics instrumentation, and real-time computational architectures.

---

## Current Research Directions

- **Deterministic FPGA Instrumentation**  
  Architectures for sensing, telemetry publication, synchronization, and visualization in real time.

- **Sensor Fusion and Environmental Awareness Systems**  
  Integration of sonar, camera, and mapping pipelines into interpretable embedded platforms.

- **Physics-Driven Simulation and Structured Computation**  
  Numerical and spatial methods for scalable simulation, especially tree-based N-body frameworks.

- **Verification and Observability Methodology**  
  Design approaches in which protocol visibility, timing contracts, and debug instrumentation are first-class outputs.

---

## Selected Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>AquaFusion_Sonar_Vision_System</h3>
      <p><b>Deterministic FPGA instrumentation for sonar, camera, and real-time HUD fusion</b></p>
      <p>
        AquaFusion investigates how real-time sensing and visualization can be organized as a deterministic FPGA pipeline.
        The system combines ultrasonic ranging, camera input, spatial map accumulation, and heads-up display rendering
        into a unified instrumentation platform.
      </p>
      <p>
        <b>Research themes:</b><br>
        synchronization contracts • SYS→PIX snapshot transfer • camera/sonar fusion • observability-first design • real-time overlay composition
      </p>
      <p>
        <b>Methodological emphasis:</b><br>
        explicit CDC boundaries, frame-stable rendering semantics, telemetry freshness tracking, and verification before hardware bring-up
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/AquaFusion_Sonar_Vision_System">Repository</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>FPGA_Signal_Control_System</h3>
      <p><b>Real-time FPGA sensing, control, and visualization architecture</b></p>
      <p>
        This project studies hardware-only sensing and display pipelines in which physical signals are sampled,
        transformed, and visualized through synchronous fixed-point processing and live VGA output.
      </p>
      <p>
        <b>Research themes:</b><br>
        real-time visualization • physical-unit mapping • UART telemetry • PWM actuation • synchronous control structure
      </p>
      <p>
        <b>Methodological emphasis:</b><br>
        deterministic timing, explicit signal contracts, and instrumentation-backed validation of behavior on hardware
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/FPGA_Signal_Control_System">Repository</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Generic_Quadtree_BarnesHut_Simulator</h3>
      <p><b>2D hierarchical N-body simulation using adaptive quadtrees</b></p>
      <p>
        A simulation framework focused on the relationship between physical modeling, approximation structure,
        and computational scaling in gravitational systems.
      </p>
      <p>
        <b>Research themes:</b><br>
        hierarchical decomposition • force approximation • numerical integration • performance-aware scientific computing
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/Generic_Quadtree_BarnesHut_Simulator">Repository</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Hashed_Octree_3D_BarnesHut</h3>
      <p><b>3D Barnes–Hut simulation with Morton-encoded hashed octrees</b></p>
      <p>
        A 3D simulation study of scalable spatial indexing and hierarchical aggregation,
        with emphasis on efficient data representation and mathematically structured implementation.
      </p>
      <p>
        <b>Research themes:</b><br>
        Morton encoding • octree organization • multipole-style approximation • spatial data structures for scientific computation
      </p>
      <p>
        <a href="https://github.com/DavidRichardson02/Hashed_Octree_3D_BarnesHut">Repository</a>
      </p>
    </td>
  </tr>
</table>

---

## Technical Areas

### Digital Systems and FPGA Architecture
- synchronous RTL design
- clock-domain crossing discipline
- real-time VGA / HDMI rendering pipelines
- UART, I2C, PWM, and sensor-interface design
- fixed-point and resource-aware arithmetic

### Embedded Instrumentation
- register-level peripheral control
- protocol timing analysis
- measurement-driven hardware bring-up
- observability and debug architecture

### Scientific and Numerical Computing
- N-body simulation
- quadtree and octree structures
- approximation methods
- performance-conscious C/C++ implementation
- model-to-implementation translation

### Documentation and Engineering Methodology
- LaTeX technical writing
- architectural contracts and timing documentation
- verification-first development workflows
- reproducible build and implementation flows

---

## Selected Results

<details>
<summary><b>Expand figures and implementation snapshots</b></summary>

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

## Documentation and Writing

A major component of the work is formal engineering documentation intended to unify:

- physical motivation
- mathematical formulation
- implementation contracts
- timing and synchronization semantics
- verification strategy
- instrumentation and empirical validation

This documentation style is used to bridge design, implementation, and analysis in a way that supports both development and technical communication.

**Featured PDF**  
[Sonar_Fusion_Signal_CAT_Thesis (3).pdf](https://github.com/user-attachments/files/24847481/Sonar_Fusion_Signal_CAT_Thesis.3.pdf)

---

## Repository Highlights

- [AquaFusion_Sonar_Vision_System](https://github.com/DavidRichardson02/AquaFusion_Sonar_Vision_System)  
  FPGA sonar + camera fusion with deterministic telemetry and HUD rendering

- [FPGA_Signal_Control_System](https://github.com/DavidRichardson02/FPGA_Signal_Control_System)  
  Real-time sensing, control, and visualization on FPGA

- [Generic_Quadtree_BarnesHut_Simulator](https://github.com/DavidRichardson02/Generic_Quadtree_BarnesHut_Simulator)  
  2D Barnes–Hut simulation using adaptive quadtrees

- [Hashed_Octree_3D_BarnesHut](https://github.com/DavidRichardson02/Hashed_Octree_3D_BarnesHut)  
  3D Barnes–Hut simulation using Morton-encoded hashed octrees

- [Automated_CSV_Data_Analysis](https://github.com/DavidRichardson02/Automated_CSV_Data_Analysis)  
  Structured data analysis workflows for modeled and experimental datasets

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DavidRichardson02&show_icons=true&hide_title=true&hide_rank=true&count_private=true&include_all_commits=true&disable_animations=true" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavidRichardson02&layout=compact&hide_title=true&langs_count=6&disable_animations=true" height="140"/>
</p>

---

## Contact

- LinkedIn: `linkedin.com/in/david-richardson-0099281b6`
- Email: `02richardsondavid@gmail.com`
- Portfolio: `davidrichardson02.github.io`

---

<p align="center">
  <b>Interested in research opportunities in digital systems, embedded instrumentation, real-time computing, and scientific hardware/software co-design.</b>
</p>
