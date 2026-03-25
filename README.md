# Planetary Gear System Design (SolidWorks)

## 📌 Overview

This project presents the design of a **planetary gear system** developed in SolidWorks. The goal was to model a transmission system and validate its motion and gear ratio through simulation.

---

## ⚙️ Key Features

* Complete 3D CAD modeling of sun, planet, ring gears, and other supporting parts.
* Assembly of a functional planetary gear train
* Verified gear ratio through SolidWorks motion simulation
* Parametric design approach for easy modification
* Smooth gear meshing with no interference

---

## 🧠 Technical Specifications

* **Gear Type:** Spur
* **Module (m):** 1 mm
* **Configuration:** Planetary Gear System

### Gear Parameters:

* **Sun Gear Teeth (Ns):** 14
* **Planet Gear Teeth (Np):** 14
* **Ring Gear Teeth (Nr):** 42

---

## 🔢 Gear Ratio Calculation

The gear ratio of a planetary gear system is given by:

[
\text{Gear Ratio} = 1 + \frac{N_r}{N_s}
]

Substituting values:

[
\text{Gear Ratio} = 1 + \frac{42}{14} = 4:1
]

The design was also tested in SolidWorks, where the observed motion confirmed the expected transmission behavior.

---

## 🎥 Simulation & Results

* Motion study performed in SolidWorks to verify rotational behavior
* Smooth transmission between gears with correct constraints
* No collision or interference detected
* Output rotation matches calculated gear ratio

---

## 📂 Project Structure

```
Planetary-Gear-System-Design-SolidWorks/ 
│ 
├── Media/ # screenshots, animations 
├── SolidWorks Files/ # .SLDPRT and .SLDASM files 
└── README.md
```

---

## 🖼️ Preview

*(Add screenshots or renders here)*

* Assembly view
* Exploded view
* Motion simulation

---

## 📌 Notes

This project focuses on the mechanical design and validation of a planetary gear system. Future improvements may include:

* Helical gear implementation
* Load and stress analysis (FEA)
* Optimization for real-world manufacturing
