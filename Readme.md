# Modeling and Simulation of Nonlinear Loads in the IEEE 34-Bus Feeder Using OpenDSS

## 📘 Overview

This project simulates the behavior of **linear, nonlinear, and switching loads** in the **IEEE 34-bus distribution feeder** using OpenDSS. It aims to analyze **power quality metrics**—such as harmonic distortion, voltage sag/swell, and response to dynamic load conditions—under realistic, time-varying scenarios. Custom spectrum definitions and time-series control logic are used to model real-world load behavior.

---

## 🧠 Objective

To study the impact of distorted and dynamic loading conditions on voltage performance in a real-world distribution feeder model by:
- Simulating various load types (linear, nonlinear, switching)
- Modeling harmonic distortions
- Performing time-series simulations (24-hour cycles)
- Analyzing power quality parameters

---

## 🏗️ System Description

- **Feeder**: IEEE 34-Bus Distribution Feeder (based on a real system in Arizona, 1992)
- **Voltage**: 24.9 kV
- **Features**:
  - Long, lightly loaded lines
  - Unbalanced loads
  - In-line voltage regulators and a short 4.16 kV section
  - Capacitor banks
  - Transformer banks with single-phase control

---

## 🧪 Load Simulation Scenarios

- **Scenario 1**: 20 constant loads
- **Scenario 2**: 20 linear loads
- **Scenario 3**: 20 switching loads
- **Scenario 4**: Mixed 68 loads (1-phase & 3-phase) with all load types

### 🔄 Time-Series Behavior

- Switching loads step up by **30–40% at start**, then drop by **20–30% after 12 hours** in a repeating cycle.
- Step simulation duration: **24 hours**

---


## 🔧 Tools & Technologies

- **OpenDSS**: Core simulation environment
- **MATLAB**: Future integration for preprocessing and power quality analysis
- **CSV Files**: Used for defining custom harmonic spectrums and load variations

---

## 📝 Author

**Soumya Ranjan Das**  
Department of Electrical Engineering  
Indian Institute of Technology (ISM) Dhanbad



This project is shared for academic and educational purposes. Please cite appropriately when reusing any part of this work.
"# Opendss_34Bus" 
"# Opendss_34Bus" 
