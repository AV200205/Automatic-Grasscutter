# Automatic-Grasscutter
Designed a low-cost automated grass cutter using motors, wheels, worm gearing, rack-and-pinion, and a cutting blade. Achieved 0.2 m/min speed with 0.968 N·m design torque, focusing on simple construction, low power use, and reduced manual effort. 





# 🌱 Grass Cutter — TA212 Project

<p align="center">
  <img width="306" height="323" alt="image" src="https://github.com/user-attachments/assets/010e11d1-766d-49bd-8e23-d7b3170ce982" />

</p>

<h3 align="center">
  Design and Development of an Automated Grass Cutter
</h3>

<p align="center">
  TA212 Project 2024–25(I) | Group G9 | IIT Kanpur
</p>

---

## 📌 Project Overview

The **Grass Cutter Project** aims to design and develop an efficient and automated system for maintaining lawns and green spaces.

The main objective is to reduce human effort while maintaining good performance with:

- Low power consumption
- Simple mechanical construction
- Low manufacturing cost
- Reliable mechanical operation

The developed system consists of a mechanical frame, wheel-drive mechanism, worm and worm-gear arrangement, rack-and-pinion mechanism, motors, motor supports and a cutting blade.

---

## 🎯 Objectives

- Design and develop an efficient grass-cutting mechanism.
- Minimize human effort required for lawn maintenance.
- Maintain low power consumption.
- Develop a simple and low-cost mechanical structure.
- Manufacture and assemble the required mechanical components.
- Perform mechanical calculations for speed, force and torque requirements.

---

## ⚙️ Project Specifications

| Parameter | Value |
|---|---|
| Vehicle Mass | 12 kg |
| Wheel Outer Diameter | 100 mm |
| Wheel Mass | 0.4 kg/piece |
| Number of Wheels | 2 |
| Rolling Friction Coefficient | 0.035 |
| Drive Mechanism Efficiency | 85% |
| Floor Slope | 0° |
| Operating Speed | 0.2 m/min |
| Safety Factor | 1.5 |
| Worm Gear Module | 1.5 |
| Worm Gear Teeth | 40 |
| Number of Worm Threads | 1 |
| Gear Ratio | 1:40 |
| Manufactured Parts | 16 |
| Project Cost | Approximately ₹13,175 |

---

## 🏗️ Mechanical Design

The grass cutter consists of the following major mechanical components:

- Frame
- Front and rear wheels
- Shaft
- Motors
- Motor supports
- Worm
- Worm gear
- Rack
- Pinion
- Rack support
- Cutting blade
- Clamps and connecting members

The assembly was designed to provide a compact structure while maintaining sufficient mechanical strength and functionality.

---

## 📐 Assembly

### Assembly Drawing

<p align="center">
  <img width="355" height="379" alt="image" src="https://github.com/user-attachments/assets/7d74626e-1533-458a-84fd-db008553ede0" />
  <img width="306" height="225" alt="image" src="https://github.com/user-attachments/assets/be631f44-c971-4e1c-87d3-df7b876f7db8" />
  <img width="281" height="206" alt="image" src="https://github.com/user-attachments/assets/c121c279-8e8c-41bd-b5fd-2f86f274a564" />



  <img src="images/assembly-drawing.png" width="700">
</p>

### Labeled Assembly

<p align="center">
  <img src="images/labeled-assembly.png" width="700">
</p>

### Approximate Assembly Dimensions

| Dimension | Value |
|---|---:|
| Overall Width | 386.41 mm |
| Overall Length | 368.77 mm |
| Overall Height | 162.37 mm |

---

# 🔩 Parts List

| Item | Quantity | Part Name | Material |
|---:|---:|---|---|
| 1 | 1 | Frameback | Generic |
| 2 | 1 | Framefront | Generic |
| 3 | 2 | Frameside | Generic |
| 4 | 2 | Clamp 1 | Generic |
| 5 | 2 | Part5_front_rod | Generic |
| 6 | 1 | Rack 212 2 | Generic |
| 7 | 1 | Pinion_final[1] | Steel |
| 8 | 2 | Front wheel | Generic |
| 9 | 2 | Part2_front_collor | Generic |
| 10 | 1 | Backwheel | Generic |
| 11 | 1 | Backwheel2 | Generic |
| 12 | 1 | Shaft | Generic |
| 13 | 1 | Motor support | Generic |
| 14 | 2 | Part1_front_arm | Generic |
| 15 | 1 | Worm Gear | Steel, Mild |
| 16 | 1 | Worm | Steel, Mild |
| 17 | 1 | Wormgearsupport | Generic |

> **Note:** The project report states that 16 parts were manufactured, while the detailed parts list contains 17 item numbers because some components have quantities greater than one.

---

# 🧮 Mechanical Calculations

## 1. Required Motor Speed

Given:

- Vehicle speed = 0.2 m/min
- Wheel diameter = 100 mm
- Gear ratio = 1:40

The required motor speed is calculated using:

$$
V_m =
\frac{V_1}
{\pi D_1 \times 10^{-3}}
\times
\frac{1}{40}
$$

Substituting:

$$
V_m =
\frac{0.2}
{\pi(100\times10^{-3})}
\times
\frac{1}{40}
$$

Therefore,

$$
\boxed{V_m \approx 25.48\ rpm}
$$

---

## 2. Rolling Force

The rolling force is calculated using:

$$
F =
9.8
\left[
(m_1+n_1m_{D1})
(\sin\alpha+\mu_1\cos\alpha)
\right]
$$

Where:

- $m_1 = 12$ kg
- $m_{D1} = 0.4$ kg
- $n_1 = 2$
- $\mu_1 = 0.035$
- $\alpha = 0^\circ$

Therefore:

$$
F \approx 4.390\ N
$$

---

## 3. Load Torque

The load torque considering the drive mechanism efficiency and gear ratio is:

$$
T_L \approx 0.6456\ N\cdot m
$$

---

## 4. Required Design Torque

Using a safety factor of 1.5:

$$
T = T_L \times S.F.
$$

$$
T = 0.6456\times1.5
$$

Therefore:

$$
\boxed{T \approx 0.9684\ N\cdot m}
$$

Hence, the required design torque is approximately:

### **0.9684 N·m**

---

# ⚙️ Rack and Pinion

## Pinion Data

| Parameter | Value |
|---|---:|
| Normal Module | 1.5 mm |
| Number of Pinion Teeth | 40 |
| Pinion Outside Diameter | 63 mm |

---

## Rack Data

| Parameter | Value |
|---|---|
| Rack Dimensions | 207 × 12 × 12 mm |
| Rack Holder Dimensions | 216 × 15 × 15 mm |
| Material | Mild Steel |
| Density | 7.85 g/cm³ |

---

# ⚖️ Mass Calculation

## Rack Mass

Volume of rack:

$$
V_{rack}
=
12\times12\times207
$$

$$
V_{rack}=29664\ mm^3
$$

Converting to cubic centimetres:

$$
V_{rack}=29.664\ cm^3
$$

Mass:

$$
m_{rack}
=
7.85\times29.664
$$

$$
\boxed{m_{rack}\approx232.3\ g}
$$

---

## Rack Holder Mass

Volume:

$$
V_{plate}
=
216\times15\times15
$$

$$
V_{plate}=48600\ mm^3
$$

$$
V_{plate}=48.6\ cm^3
$$

Mass:

$$
m_{plate}
=
7.85\times48.6
$$

$$
\boxed{m_{plate}\approx381.5\ g}
$$

---

## Total Mass

$$
m_{total}
=
232.3+381.5
$$

$$
\boxed{m_{total}=613.8\ g}
$$

Converting to kilograms:

$$
m_{total}=0.6138\ kg
$$

---

## Gravitational Force

The gravitational force is:

$$
F=mg
$$

Using:

$$
m=0.6138\ kg
$$

and

$$
g=9.81\ m/s^2
$$

Therefore:

$$
F=0.6138\times9.81
$$

$$
\boxed{F\approx6.021\ N}
$$

---

# 🏭 Manufacturing Processes

The major manufacturing processes used in the project were:

### Milling
- Worm manufacturing
- Rack and pinion manufacturing

### Turning
- Shaft and cylindrical components

### Drilling
- Frame and mechanical component holes

### Assembly
- Integration of frame
- Motors
- Wheels
- Gear mechanism
- Cutting mechanism

---

# 💰 Cost Analysis

| Component / Process | Cost |
|---|---:|
| Mild Steel — 12.9 kg × ₹100/kg | ₹1,290 |
| Motors — 2 × ₹600 | ₹1,200 |
| Blade | ₹100 |
| Motor Holders — 2 × ₹50 | ₹100 |
| Electric Kit | ₹1,000 |
| Milling | ₹1,000 |
| Turning | ₹600 |
| Drilling | ₹375 |
| Labour | ₹7,500 |
| **Detailed Total** | **₹13,165** |

> The introduction of the project report states the project cost as **₹13,175**, while the detailed cost calculation gives **₹13,165**.

---

# 🔬 Project Methodology

```text
                 PROJECT REQUIREMENTS
                         │
                         ▼
                Mechanical Design
                         │
                         ▼
               CAD / Assembly Design
                         │
                         ▼
            Speed & Torque Calculations
                         │
                         ▼
               Component Selection
                         │
                         ▼
                  Manufacturing
                         │
                         ▼
                     Assembly
                         │
                         ▼
                    Testing
                         │
                         ▼
              Performance Evaluation
