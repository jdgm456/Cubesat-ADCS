# 🛰️ Cubesat-ADCS
This repository documents the development of a closed-loop Attitude Determination and Control System (ADCS) simulation for a CubeSat-scale spacecraft using MATLAB and Simulink.

The simulation models realistic 6-DOF perturbed dynamics in Low Earth Orbit (LEO) and implements sensor fusion (Kalman filtering) for attitude estimation. Initial control strategies use PID control, with plans to explore optimal control approaches (LQR, etc.) later.

---

## 🚀 Project Goals

- Simulate realistic 6-DOF orbital and attitude dynamics for a CubeSat in LEO  
- Design and implement attitude estimation using Kalman filtering techniques  
- Develop and tune control algorithms (PID initially, then LQR)  
- Prepare the simulation for eventual Hardware-in-the-Loop (HIL) testing via embedded code generation (MATLAB Coder)

---

## 🧰 Tools & Technologies

- MATLAB  
- Simulink  
- MATLAB Coder (planned for future embedded code generation)

---

## 📌 Current Status

- Researching spacecraft rotational dynamics (quaternions, Euler angles) and LEO perturbations  
- Exploring Kalman filter design and its integration into a closed-loop Simulink simulation  
- Starting PID controller development to stabilize spacecraft attitude  
- Repository structure and Simulink model initialization underway

---

## 🔭 Planned Milestones

- Implement extended Kalman filter (EKF) for improved non-linear estimation  
- Explore LQR control and other optimal strategies  
- Integrate realistic actuator models (reaction wheels, magnetorquers)  
- Use MATLAB Coder to generate embedded C code for deployment on a microcontroller  
- Conduct Hardware-in-the-Loop (HIL) testing using a CubeSat testbed

---

## 📂 Repo Structure (in progress)

```plaintext
Cubesat-ADCS/
├── README.md
├── models/                # Simulink files (dynamics, control, estimation)
├── scripts/               # MATLAB utility scripts (e.g. quaternions, plotting)
├── estimation/            # Kalman filter models
├── control/               # PID, LQR, and other control implementations
├── docs/                  # Notes, derivations, background research
└── references/            # Technical papers and resource links
