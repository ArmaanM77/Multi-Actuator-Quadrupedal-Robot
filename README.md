# Multi-Actuator Quadrupedal Robot — CAD Design Project

## Overview

This repository contains the complete CAD design work for a **Quadrupedal Multi-Actuator Robot**, developed as part of the **MIT-101 (TEB)** project under the guidance of **Prof. P. M. Pathak, MIED, IIT Roorkee**.

The project focuses on the **3D CAD modelling, assembly design, and mechanism-level exploration** of a quadrupedal robot intended for dynamic locomotion, impact absorption, and jumping-based applications. The design includes individual actuator models, leg mechanisms, chassis structures, and full robot assemblies.

The CAD files uploaded in this repository include models for:

- Individual actuator assemblies
- Leg mechanism assemblies
- Full quadruped robot assemblies
- Exploded views and mechanism-level CAD layouts

The project scope included CAD modelling of parts, assembly modelling, exploded views, motion study of mechanisms, and comparative analysis across actuator and linkage choices. :contentReference[oaicite:0]{index=0}

---

## Project Objective

The main objective of this project was to design a mechanically realistic quadrupedal robot architecture with emphasis on:

- Impact absorption during landing
- Jumping and dynamic locomotion capability
- Compact actuator packaging
- Backdrivable joint design
- Low-inertia leg structures
- Compliant leg behaviour for shock transfer
- CAD-to-prototype reproducibility

---

## Design Considerations

The quadruped was designed keeping in mind the mechanical requirements of legged robotic systems, especially those exposed to repeated ground impacts during jumping or fast locomotion.

Key design considerations included:

- **High torque at leg joints**
- **Low inertia at links**
- **Responsive force transfer**
- **Compliant legs for shock absorption**
- **Backdrivability for assisted impact absorption**
- **Compact and manufacturable CAD architecture**

The leg design uses a two-link structure, with a rigid upper link and a compliant lower link. The compliant section behaves similar to a spring-assisted prismatic mechanism, helping with shock absorption, temporary energy storage, and improved locomotion stability.

---

## Robot Architecture

The robot architecture is inspired by quadrupedal legged systems such as the **Cheetah-Cub architecture**. The design explores multi-actuator leg control, compliant lower-leg mechanisms, and compact actuator placement for practical quadruped locomotion.

The leg mechanism considers typical quadrupedal degrees of freedom:

1. **Hip Abduction / Adduction**
2. **Hip Pitch**
3. **Knee Joint Motion**

The knee actuation and leg motion were explored using linkage-based mechanisms, including parallel-link and ball-screw-assisted concepts.

---

## Actuator Exploration

Multiple actuator concepts were studied and modelled for comparison:

| Actuator Type | Key Advantage | Limitation |
|---|---|---|
| Quasi Direct Drive (QDD) | High transparency and good control | Lower reduction than high-ratio drives |
| Cycloidal Drive | Compact high reduction | Friction, backlash, bearing complexity |
| Capstan Drive | Lightweight and highly backdrivable | Rope tensioning and slip issues |
| Harmonic Drive | High reduction and compact form | Lower backdrivability and higher friction |

The final design direction gives importance to **spur-geared Quasi Direct Drive actuators** for the quadruped legs due to their better backdrivability, simpler fabrication, and suitability for impact-heavy motion.

Cycloidal drives were also considered for higher torque-density applications such as a robotic arm attachment.

---

## Engineering Design Decisions

### Quasi Direct Drive for Legs

QDD was preferred for the quadruped leg actuation because it provides:

- Better backdrivability
- Lower gear friction
- Easier impact energy transfer
- Simpler manufacturing
- More suitable active compliance control

This is important for a quadruped robot because leg joints must tolerate repeated ground impacts without becoming overly rigid or mechanically fragile.

### Spur Gears over Helical Gears

Spur gears were preferred over helical gears for the QDD actuator because:

- Spur gears do not generate axial thrust
- They require simpler bearing support
- They offer better backdrivability due to lower sliding friction
- They are easier to fabricate and align
- They are more suitable for impact-heavy robotic leg joints

### Cycloidal Drive for Robotic Arm

Cycloidal drives were considered for the robotic arm because they offer:

- High torque density
- Strong shock resistance
- Compact packaging
- Better load distribution across contact points

---

## Repository Contents

This repository contains CAD files related to:

```text
/Actuators
    - QDD actuator models
    - Cycloidal drive models
    - Capstan drive models
    - Harmonic drive concepts

/Leg Assemblies
    - Compliant leg mechanism
    - Parallel linkage mechanism
    - Ball screw assisted mechanism

/Robot Assemblies
    - Full quadruped assembly
    - Quadruped with robotic arm concept
    - Exploded assembly views

/Documentation
    - Project presentation
    - Design comparison references---
```
## CAD Design Workflow

The CAD development was carried out in a modular manner so that each subsystem could be designed, reviewed, and assembled independently before integration into the full robot model.

The workflow followed was:

1. Design and modelling of individual actuator components
2. Assembly of actuator mechanisms
3. Development of leg linkage and compliant leg structures
4. Integration of actuators with leg assemblies
5. Full quadruped chassis and body assembly
6. Exploded views for better understanding of part placement
7. Mechanism study for motion feasibility and design comparison

---

## Key Features

- Complete 3D CAD modelling of a quadrupedal robot
- Multi-actuator design exploration
- Modular leg and actuator assemblies
- Compliant lower-leg mechanism for impact absorption
- QDD-based leg actuation concept
- Comparative study of QDD, cycloidal, capstan, and harmonic actuators
- Conceptual quadruped design with robotic arm integration
- Full robot assembly and exploded CAD views

---

## Applications Considered

The design was developed keeping in mind applications where legged robots experience repeated dynamic loading, such as:

- Jumping and landing motions
- Rough-terrain locomotion
- Impact-heavy robotic movement
- Research in bio-inspired quadrupedal mechanisms
- Mechanism design for agile legged robots

---

## Project Guide

**Prof. P. M. Pathak**  
Department of Mechanical and Industrial Engineering  
Indian Institute of Technology Roorkee

---

## Group Members

- **Armaan Mahajan** — 24113022
- **Sai Thanveer** — 24117051
- **Lakshya Kumar** — 24117068
- **Mahiraj Seervi** — 24113078

---

## Repository Link

```text
https://github.com/ArmaanM77/Multi-Actuator-Quadrupedal-Robot.git
