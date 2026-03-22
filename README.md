# Spacecraft Systems Engineering: Subsystem Design & Analysis 🚀🛰️

[![Systems](https://img.shields.io/badge/Domain-Spacecraft_Systems-blue.svg)]()
[![Simulation](https://img.shields.io/badge/Simulation-MATLAB-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

A comprehensive collection of analytical and numerical studies covering the preliminary design and sizing of core spacecraft subsystems. 

Developed for the **Spacecraft Systems (Sistemas de Vehículos Espaciales)** course within the Master's Degree in Aeronautical Engineering at Universidad de Sevilla.

---

## 📌 Project Overview

Designing a successful space mission requires a multidisciplinary approach, balancing the capabilities and constraints of various interconnected subsystems. This repository contains a structured, four-part project that tackles the preliminary design of a spacecraft from launch to interplanetary operation.

### 🎯 Core Modules

#### 1. Launch System (Ascent & Orbit Injection)
* Analysis of the Falcon Heavy launch vehicle using a sequential multi-stage model.
* Calculation of the total $\Delta V$ budget and payload ratios.
* Simulation of the ascent trajectory considering gravity turn maneuvers and an exponential atmospheric drag model.
* Hohmann transfer optimization for Geostationary Transfer Orbit (GTO) injection.

#### 2. Propulsion System (Interplanetary Mission to Venus)
* **Chemical Monopropellant (Hydrazine):** Sizing of an impulsive transfer to Venus, including hyperbolic escape, Hohmann transfer, aerobraking, and periapsis raising.
* **Electric Propulsion:** Modeling a continuous, low-thrust spiraling trajectory to achieve the same final orbit, comparing time-of-flight and propellant mass savings against the chemical alternative.

#### 3. Power System (Sun-Synchronous LEO Satellite)
* **Solar Array Sizing:** Selection and sizing of multi-junction solar cells (AZUR SPACE/SOLAERO) factoring in End-of-Life (EOL) degradation, albedo, and worst-case operating temperatures.
* **Battery Sizing:** Capacity planning for Li-ion batteries to sustain satellite operations during orbital eclipses, adhering to strict Depth of Discharge (DOD) constraints.

#### 4. Thermal Control System (Venus Orbit)
* **Quasi-Steady & Transient Analysis:** Modeling the thermal balance of a satellite in low Venus orbit, subjected to direct solar flux, planetary albedo, and planetary infrared radiation.
* **Material Selection:** Evaluating different surface coatings (e.g., aluminized Teflon, anodized aluminum) to maintain internal temperatures within operational limits across all mission phases.

## 📂 Repository Contents

* **`docs/`**: Contains the official assignment statements and the comprehensive project reports (Reports 1 to 4) detailing the theoretical background, mathematical models, and final results for each subsystem.
* **`src/`** *(Coming soon)*: Will contain the MATLAB scripts used to integrate the launch trajectories, perform the iterative sizing loops, and simulate the thermal transients.

## 👨‍💻 Authors

* **Antonio Ortega López**
* **Alejandro Rivera Míguez**
* **Pablo Sánchez Mora**
* **Jorge Soria Sánchez**
* **Narciso Valverde González**

---

Professor: **Antonio Franco Espín**  
Master in Aeronautical Engineering | Universidad de Sevilla

---
*Disclaimer: This is an academic project. The calculations and models provided are intended for educational demonstration of aerospace systems engineering.*
