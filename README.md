# Design of Cyber-Physical Systems in Manufacturing

## Course Overview

The goal of this course is to integrate practical and theoretical aspects in an international and interdisciplinary setting. Participants will engage in the design, development, and deployment of a **cyber-physical system (CPS)** for manufacturing, working collaboratively in teams to build a **digital twin** for a set of robots using MATLAB Simulink. The course emphasizes both simulation and real-world implementation, providing hands-on experience with industrial series production and robot commissioning.

---

## Course Objectives

1. **Development of a Cyber-Physical System**  
   Learn how to design, simulate, and deploy CPS solutions tailored to manufacturing.

2. **Interdisciplinary Collaboration**  
   Work in a team with diverse international backgrounds, combining skills from various disciplines.

3. **Digital Twin Development**  
   Build and model a digital twin using MATLAB Simulink for a set of robots.

4. **Industrial Series Production Simulation**  
   Gain insights into simulating and optimizing production workflows in an industrial setting.

5. **Robot Commissioning**  
   Apply your knowledge to program and commission physical robots for manufacturing tasks.

---

## Course Structure

### 1. **Kick-Off Workshop**
- **When**: Mid-December (2 days)  
- **Where**: Twente  
- Overview of course goals and team formation.

### 2. **Lectures and Hands-On Sessions**
- Topics include:  
  - Design of Cyber-Physical Systems  
  - Recap of Production Systems  
  - Introduction to Simulink  
  - Modeling and Implementation of Digital Twins  

### 3. **Seminars**
- **Number**: 3 sessions  
- **Focus**: Varies based on the outcomes of the Kick-Off Workshop.  

### 4. **Project Group Meetings**
- Regular meetings to track progress, share updates, and align on objectives.

### 5. **Wrap-Up/Closing Workshop**
- **When**: January (1 day)  
- **Where**: RPTU  
- Present final projects, discuss outcomes, and receive feedback.

---

## Tools and Technologies

- **MATLAB Simulink**: For modeling and simulating digital twins.
- **Robots**: Hands-on experience with commissioning physical robots.
- **Collaboration Tools**: GitLab for version control, issue tracking, and documentation.

# Repository Structure

```plaintextcps-development/
├── src/
│   ├── controllers/        # UT: Robot control logic and implementations
│   ├── models/             # 3D models (UT), digital twin models/MATLAB Simulink (RPTU)
├── docs/
│   ├── design_documents/   # UT: Design 3D model, assembly line, layout descriptions 
│   └── user_guides/        # Guides for using models, simulations, and robots
|   └── assignment_sheet/   # assignment sheet from prof/module handbook.     
├── design/                 # UT: Layouts and 3D designs models, solidwork parts
├── experiments/            # UT: Experiment data and analysis results
├── config/                 # RPTU: Configuration files for simulations and robot deployment
├── tests/                  # Unit and integration test cases: Digital Twin (RPTU), physical test scenario (UT)
├── results/                # Outputs from simulations, current findings
|   └── Presentation/       # milenstone, is-state, intermediate solution
└── README.md               # Project documentation
