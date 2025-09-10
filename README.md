# 🛰️ Cubesat-ADCS
Repository documents the development of a closed-loop simulation for a CubeSat-scale Attitude Determination &amp; Control System (ADCS) using Simulink. The project focuses on modeling realistic perturbed dynamics and implementing Kalman filter-based sensor fusion for attitude estimation. Initial control strategies include PID control, then LQR later on

## Goals
- ** Simulate realistic perturbed dynamics for cubesat in Low Earth orbit
- ** Prepare for future hardware deployment

## Tools
- ** Simulink
- ** MATLAB

## Current Status
- ** Early research phase in the aspect of the perturbed dynamics of a cubesat in LEO
- ** Early research phase in estimation methods (Kalman filter), in how to employ in closed loop simulink simulation
- ** Early research phase in control algorithm development for cubesat, PID implementation aiming to adjust the attitude


## Future Goals
- ** Employ more advanced estimation filters such as the extended kalman filter to handle more aggresive non-linear dynamics
- ** Look into optimal control strategies, starting first with LQR
- ** Hardware deployment, use MATLAB's embedded coder to obtain embedded C code to deploy on microcontroller for Hardware in the Loop simulation (HIL)
