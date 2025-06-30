# 🚁 Tiltrotor Gearbox Dynamics — MATLAB Simulation Project

A simulation-based analysis of the **tiltrotor gearbox transmission system** inspired by the Leonardo AW609 VTOL aircraft. Developed as part of a university computer project, this repository contains mathematical modeling, MATLAB simulations, linearizations, and system response analyses for a dual-rotor gear train.

## 📌 Project Overview

This project simulates a key component of the **transmission system** that transfers torque between the two rotors of a tiltrotor aircraft. The mechanical model was derived using Newtonian dynamics and implemented in MATLAB using ODE solvers. The system response to varying input torques is studied, including linearized and nonlinear models.

### 🔍 Core Objectives

- Model the nonlinear dynamics of a 3 DOF tiltrotor gearbox.
- Simulate the response to step input torques using MATLAB’s `ode45`.
- Linearize the system about equilibrium and compare system behaviors.
- Extract the transfer function, poles, zeros, natural frequency, and damping ratio.
- Extend the analysis to account for gear tooth deformation (extra credit).

## 📊 Features

- ✅ Nonlinear state-space modeling
- ✅ MATLAB ODE simulation (`ode45`)
- ✅ Linearization and step response comparison
- ✅ Transfer function and Bode analysis
- ✅ Gear stiffness modeling as an extension


## 🧮 Equations Modeled

- 3 DOF system modeled via Newton's Laws
- State-space variables:  
  `q₁ = θ̇₁`, `q₂ = θ₁ - θ₂`, `q₃ = θ̇₃`
- Coupling torque and deformation modeled with additional spring-damper elements

## 🧑‍💻 Contributors

| Name                | Roll Number |
|---------------------|-------------|
| Aryamann Srivastava | 230211      |
| Varun Sathaye       | 230934      |
| Yug Vora            | 231175      |
| Arul Gupta          | 230207      |


## 📂 Folder Structure

1.  Group Project.pdf
2.  README.md


## 📌 How to Run

1. Open MATLAB.
2. Load the scripts in `Group Project.pdf`.
3. Run `main.m` or open and execute the sections manually.
4. Observe response graphs for step inputs.

> MATLAB R2023a or higher is recommended.

## 📜 License

This project is academic in nature and falls under the [MIT License](LICENSE).

---
