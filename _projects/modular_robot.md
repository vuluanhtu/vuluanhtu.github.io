---
layout: page
title: Modular Self-Reconfigurable Robotic System
description: Novel mobile, modular, and self-reconfigurable robotic system with morphability capability
img: assets/img/projects/modular_robot/MSR-module-3D-design.jpg
importance: 1
category: design
related_publications: true
toc:
  sidebar: left
images:
  photoswipe: true
---

> 📅 Aug 2021 - May 2023 | 🎓 Master's Thesis | 🏛️ Purdue University Fort Wayne
{: .block-tip }

## Project Overview
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

This project represents my Master's thesis research, focusing on the design, development, and testing of a **novel mobile, modular, and self-reconfigurable robotic system**. The system is capable of adapting its configuration to perform various tasks in dynamic environments, demonstrating significant improvements in versatility and efficiency compared to traditional robotic systems.

---

## Key Achievements
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

> **📚 Comprehensive Literature Review** — Researched and analyzed over **100 referenced research papers** on modular robotics
{: .block-tip }

> **⚙️ Novel Mechanism Design** — Designed a linear actuator and gear transmission system following **ASME standards** to control **6 degrees of freedom** with only **2 DC motors**
{: .block-tip }

> **🧮 First-Principles Analysis** — Calculated power transmission capacity of gears, stack-up tolerances, and analyzed stress on critical components
{: .block-tip }

> **💻 FEA Validation** — Simulated motion and stress in **SolidWorks**, iteratively optimizing the design based on simulation results
{: .block-tip }

> **🔧 Physical Prototype** — 3D printed and assembled a **functional prototype** of 1 robot module
{: .block-tip }

> **📄 Academic Publication** — Published findings in a **34,000-word thesis** and **peer-reviewed journal article** (MDPI Actuators)
{: .block-tip }

---

## Technical Approach
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Mechanical Design
{: .mt-4 .mb-3 .font-weight-bold }

The core innovation lies in the actuator and transmission system design. By employing a clever gear arrangement and linear actuation mechanism, the system achieves **6-DOF motion control** using only **two motors** - significantly reducing weight, complexity, and power requirements compared to conventional designs.

**Key Design Features:**

- Custom linear actuator mechanism
- ASME-compliant gear transmission system
- Optimized for 3D printing and assembly
- Modular interface for multi-robot configurations

<div class="pswp-gallery" id="gallery-module-design">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-module-3D-design.jpg' | relative_url }}" data-pswp-width="1414" data-pswp-height="770" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-module-3D-design.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Robot Module 3D Design" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-module-3D-design-inside-view.jpg' | relative_url }}" data-pswp-width="1537" data-pswp-height="1165" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-module-3D-design-inside-view.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Module Internal Components" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
    Complete 3D CAD model of the robot module (left) and internal view showing actuator and transmission system (right)
</div>

<div class="pswp-gallery" id="gallery-components">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-gearbox-3D-design.jpg' | relative_url }}" data-pswp-width="1705" data-pswp-height="1740" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-gearbox-3D-design.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Gearbox Design" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-DM-3D-design.jpg' | relative_url }}" data-pswp-width="1799" data-pswp-height="1509" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-DM-3D-design.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Docking Mechanism Design" />
      </a>
    </div>
  </div>
  <div class="caption">
    ASME-compliant gear transmission system to control 6 degrees of freedom with only 2 DC motors (left) and docking mechanism 3D design inspired from mechanical pen clicking mechanism (right)
  </div>
  <div class="row justify-content-sm-center mt-3">
    <div class="col-sm-8">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-genderless-docking-mechanism.jpg' | relative_url }}" data-pswp-width="1922" data-pswp-height="1444" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-genderless-docking-mechanism.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Genderless Docking Mechanism" />
      </a>
    </div>
  </div>
  <div class="caption">
    Innovative genderless docking mechanism allowing modules to connect in multiple orientations
  </div>
</div>

---

### Configuration Morphability
{: .mt-4 .mb-3 .font-weight-bold }

One of the key features is the system's ability to reconfigure into different formations for various tasks:

<div class="pswp-gallery" id="gallery-configurations">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-chain-config.jpg' | relative_url }}" data-pswp-width="2052" data-pswp-height="1912" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-chain-config.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Chain Configuration" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-hybrid-config.jpg' | relative_url }}" data-pswp-width="2090" data-pswp-height="2440" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-hybrid-config.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Hybrid Configuration" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
    Different robot configurations: chain formation for snake-like locomotion (left) and hybrid configuration for complex tasks (right)
</div>

---

### Analysis & Validation
{: .mt-4 .mb-3 .font-weight-bold }

Extensive simulation work was performed to validate the design before prototyping:

- **Kinematic Analysis** - Motion simulation to verify degrees of freedom
- **Structural FEA** - Stress analysis on critical load-bearing components
- **Tolerance Analysis** - Stack-up calculations to ensure assembly feasibility
- **Power Transmission** - Gear capacity calculations following mechanical design standards

First-principles calculations for gear sizing and torque requirements:

<div class="pswp-gallery" id="gallery-calculations">
  <div class="row">
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-gear-size-calculation.jpg' | relative_url }}" data-pswp-width="2007" data-pswp-height="612" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-gear-size-calculation.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Gear Size Calculation" />
      </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-lift-torque-calculation.jpg' | relative_url }}" data-pswp-width="2090" data-pswp-height="746" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-lift-torque-calculation.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Lift Torque Calculation" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
    Hand calculations for gear sizing and transmission ratios (left) and torque analysis for lifting capacity (right)
</div>

<div class="pswp-gallery" id="gallery-performance">
  <div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-power-speed-chart.jpg' | relative_url }}" data-pswp-width="752" data-pswp-height="452" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-power-speed-chart.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Motor Power-Speed Analysis" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
    Power-speed performance chart for motor selection and transmission optimization
</div>

SolidWorks motion simulation demonstrating the autonomous docking mechanism:

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/projects/modular_robot/MSR-docking-simulation.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
    </div>
</div>
<div class="caption">
    Animation showing the docking sequence between two robot modules
</div>

---

### Prototyping
{: .mt-4 .mb-3 .font-weight-bold }

All components were designed for 3D printing assembly, including:

- Custom-designed structural parts
- Integration of purchased components (motors, bearings, springs, fasteners)
- Assembly verification and functional testing

<div class="pswp-gallery" id="gallery-prototype">
  <div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
      <a href="{{ '/assets/img/projects/modular_robot/MSR-prototype.jpg' | relative_url }}" data-pswp-width="1952" data-pswp-height="777" target="_blank">
        <img src="{{ '/assets/img/projects/modular_robot/MSR-prototype.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Physical Prototype" />
      </a>
    </div>
  </div>
</div>
<div class="caption">
    Functional prototype: 3D-printed components assembled with motors and mechanical parts
</div>

---

## Technical Skills Demonstrated
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

- **CAD Modeling** - Complex 3D assemblies in SolidWorks
- **Mechanism Design** - Kinematic and dynamic analysis
- **FEA Simulation** - Structural validation and optimization
- **Standards Compliance** - ASME mechanical design standards
- **Research Methodology** - Systematic literature review and analysis
- **Technical Writing** - 34,000-word thesis, journal publication
- **Prototyping** - 3D printing, assembly, and testing

---

## Publications
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

> **📄 Journal Article**
>
> Vu, L. A. T., Bi, Z., Mueller, D., & Younis, N. (2023). "Modular Self-Configurable Robots—The State of the Art." _Actuators_, 12(9), 361.
>
> [https://doi.org/10.3390/act12090361](https://doi.org/10.3390/act12090361)
{: .block-tip }

> **🎓 Master's Thesis**
>
> Vu, L. A. T. (2023). "A Mobile, Modular, and Self-Reconfigurable Robotic System with Morphability." Purdue University Graduate School.
>
> [https://doi.org/10.25394/PGS.24784308](https://doi.org/10.25394/PGS.24784308)
{: .block-tip }

---

## Impact
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

This research contributes to the field of modular robotics by demonstrating a practical approach to morphable robot design. The system's ability to reconfigure itself opens applications in:

- 🚨 **Search and Rescue Operations** - Adapting to navigate complex disaster environments
- 🏭 **Adaptive Manufacturing Systems** - Reconfiguring for different production tasks
- 🚀 **Space Exploration** - Morphing to handle various terrains and mission requirements
- ☢️ **Hazardous Environment Inspection** - Changing shape to access dangerous or contaminated areas

> **Impact Statement**
>
> The publication in MDPI Actuators Journal ensures this work is accessible to the broader research community and serves as a foundation for future developments in reconfigurable robotics.
{: .block-tip }
