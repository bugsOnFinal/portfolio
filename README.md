# Aerospace Engineering Portfolio
**Anwak Manoj Kumar** | Aeronautical Engineering, MIT Manipal  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/anwak-manoj-kumar-580ba7314) [![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:anwak05@gmail.com)

---

## Overview

This repository showcases selected CAD, FEA, and CFD work from my projects at AeroMIT (SAE Collegiate Design Team) and independent research at Manipal Institute of Technology. All structural and aerodynamic simulations were carried out in ANSYS Mechanical and ANSYS Fluent; all CAD models were developed in SolidWorks.

> **Note:** Full CAD and simulation files are not hosted here due to competition confidentiality and ongoing publication restrictions. Screenshots of key results are provided for each project.

---

## CAD

All models designed in **SolidWorks**.

| Model | Description |
|-------|-------------|
| SAE Aero Design Aircraft — Full Internal Structure | Laser-cut balsa rib and spar framework with carbon fibre reinforcement, designed for SAE Aero Design East 2026 (World Rank 4 Overall) |
| AeroMIT RC Aircraft (Conventional) | Conventional tractor configuration RC aircraft — two design iterations shown |
| Flying Wing | Blended wing body concept for aerodynamic efficiency studies |
| Aircraft Fuselage Internal Structure | Frame and longeron layout with skin cutaway views |

### Previews

<img src="CAD/images/sae_aero_design_full_structure.png" width="700"/>
<p><em>SAE Aero Design East 2026 aircraft — full internal structure (SolidWorks)</em></p>

<img src="CAD/images/rc_aircraft_v1.png" width="700"/>
<p><em>AeroMIT RC aircraft — early configuration</em></p>

<img src="CAD/images/rc_aircraft_v2.png" width="700"/>
<p><em>AeroMIT RC aircraft — refined configuration with propeller</em></p>

<img src="CAD/images/flying_wing.png" width="700"/>
<p><em>Flying wing / blended wing body concept</em></p>

<img src="CAD/images/fuselage_internal_v1.png" width="700"/>
<p><em>Aircraft fuselage internal structure — frame and longeron layout</em></p>

<img src="CAD/images/fuselage_internal_v2.png" width="700"/>
<p><em>Aircraft fuselage internal structure — alternate view</em></p>

---

## FEA

All analyses performed in **ANSYS Mechanical 2024 R2** (Static Structural, Modal, Explicit Dynamics, Random Vibration).

| Analysis | Component | Key Result |
|----------|-----------|------------|
| Static Structural — Von Mises Stress | Wing rib (optimised) | Max stress: 53.2 MPa |
| Static Structural — Total Deformation | Nose landing gear (impact load) | Max deformation: 14.1 mm |
| Static Structural — Total Deformation | Full aircraft airframe | Max deformation: 25.8 mm |
| Static Structural — Total Deformation | RC aircraft fuselage and tail structure | Max deformation: 16.9 mm |
| Static Structural — Total Deformation | Quadcopter frame (landing impact) | Max deformation: 0.04 mm |

### Previews

<img src="FEA/images/wing_rib_von_mises.png" width="700"/>
<p><em>Wing rib — equivalent (von Mises) stress, static structural. Max: 53.2 MPa</em></p>

<img src="FEA/images/nose_gear_deformation.png" width="700"/>
<p><em>Nose landing gear — total deformation under impact load. Max: 14.1 mm</em></p>

<img src="FEA/images/full_aircraft_deformation.png" width="700"/>
<p><em>Full aircraft airframe — total deformation, static structural. Max: 25.8 mm</em></p>

<img src="FEA/images/fuselage_tail_deformation.png" width="700"/>
<p><em>RC aircraft fuselage and tail — total deformation. Max: 16.9 mm</em></p>

<img src="FEA/images/quadcopter_landing_deformation.png" width="700"/>
<p><em>Quadcopter frame — total deformation, landing impact. Max: 0.04 mm</em></p>

---

## CFD

All simulations performed in **ANSYS Fluent**.

| Simulation | Description |
|------------|-------------|
| Full Aircraft — Velocity Pathlines | 3D RANS simulation at 25 m/s freestream; velocity pathlines showing wake structure, wingtip vortices, and fuselage separation |

### Previews

<img src="CFD/images/aircraft_velocity_pathlines.png" width="700"/>
<p><em>Full aircraft CFD — velocity magnitude pathlines (ANSYS Fluent). Freestream: 25 m/s</em></p>

---

## Publications & Software

| Title | Venue | Status |
|-------|-------|--------|
| FALCON: Framework for Airfoil CFD and anaLysis OptimizatioN | ICAS 2026, Sydney | Accepted — Oral Presentation (Sep 2026) |
| Advances in Flow–Structure Interaction and Multiphysics Applications: An Immersed Boundary Perspective | *Fluids*, MDPI (Q2) | Published 2025 |
| Recent Developments in the Immersed Boundary Method for Complex Fluid–Structure Interactions: A Review | *Fluids*, MDPI (Q2) | Published 2025 |

FALCON source code: [github.com/Prisha22/FALCON](https://github.com/Prisha22/FALCON) *(co-developed — hosted on collaborator's account)*  
Registered Software: SW-47114/2025-CO

---

## Software Used

- **SolidWorks** — 3D modelling and assembly
- **ANSYS Mechanical 2024 R2** — Static Structural, Modal, Explicit Dynamics, Random Vibration
- **ANSYS Fluent** — CFD simulation and post-processing
- **Python / SU2 / GMSH** — Automated CFD pipeline (FALCON)
