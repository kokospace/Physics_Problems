# Projectile Motion Analysis

This repository contains the mathematical derivation and a Python simulation for a projectile motion problem.

## 1. Problem Statement
A projectile is fired from the ground with:
* **Initial Velocity ($v_0$):** $100 \text{ m/s}$
* **Launch Angle ($\theta$):** $37^\circ$
* **Gravity ($g$):** $9.81 \text{ m/s}^2$

---

## 2. Mathematical Derivation

### Initial Velocity Components
The velocity is resolved into horizontal ($x$) and vertical ($y$) components:
* $v_{0x} = v_0 \cos(37^\circ) \approx 79.86 \text{ m/s}$
* $v_{0y} = v_0 \sin(37^\circ) \approx 60.18 \text{ m/s}$

### Differential Equations of Motion
Using Newton's Second Law ($F = ma$):

**Horizontal Direction ($x$):**
No horizontal forces act on the projectile ($a_x = 0$):
$$\frac{d^2x}{dt^2} = 0 \implies \frac{dx}{dt} = v_{0x} \implies x(t) = v_{0x}t$$

**Vertical Direction ($y$):**
Gravity acts downwards ($a_y = -g$):
$$\frac{d^2y}{dt^2} = -g \implies \frac{dy}{dt} = v_{0y} - gt \implies y(t) = v_{0y}t - \frac{1}{2}gt^2$$



---

## 3. Key Calculations

| Parameter | Formula | Result |
| :--- | :--- | :--- |
| **Time of Flight** | $T = \frac{2v_{0y}}{g}$ | $\approx 12.27 \text{ s}$ |
| **Max Height** | $H_{max} = \frac{v_{0y}^2}{2g}$ | $\approx 184.6 \text{ m}$ |
| **Range** | $R = \frac{2v_{0x}v_{0y}}{g}$ | $\approx 979.7 \text{ m}$ |

---
