# 🚀 Projectile Motion Analysis & Simulation

This project provides a comprehensive physical and mathematical analysis of **projectile motion**, including a Python-based animation.

## 📝 Problem Definition
A projectile is launched from the ground with the following parameters:
* **Initial Velocity ($v_0$):** $100 \text{ m/s}$
* **Launch Angle ($\theta$):** $37^\circ$
* **Gravity ($g$):** $9.81 \text{ m/s}^2$ (No air resistance)

---

## 📐 Detailed Mathematical Derivation

### 1. Initial Velocity Components
The velocity is a vector. We must resolve it into horizontal ($x$) and vertical ($y$) components using trigonometry:
* **Horizontal:** $v_{0x} = v_0 \cdot \cos(37^\circ) = 100 \cdot 0.8 \approx 80 \text{ m/s}$
* **Vertical:** $v_{0y} = v_0 \cdot \sin(37^\circ) = 100 \cdot 0.6 \approx 60 \text{ m/s}$



### 2. Differential Equations of Motion
Based on Newton's Second Law ($F = ma$):

**Horizontal Direction ($x$):**
Since there is no air resistance, $F_x = 0$, meaning acceleration is zero.
$$\frac{d^2x}{dt^2} = 0 \implies \frac{dx}{dt} = v_{0x} \implies x(t) = v_{0x} \cdot t$$

**Vertical Direction ($y$):**
Gravity is the only force acting downwards ($a_y = -g$).
$$\frac{d^2y}{dt^2} = -g \implies \frac{dy}{dt} = v_{0y} - gt \implies y(t) = v_{0y}t - \frac{1}{2}gt^2$$

---

## 📊 Calculated Results

| Parameter | Calculation Logic | Result |
| :--- | :--- | :--- |
| **Time of Flight ($T$)** | Set $y(t) = 0$ | **$12.27 \text{ s}$** |
| **Max Height ($H_{max}$)** | Set $v_y(t) = 0$ | **$184.6 \text{ m}$** |
| **Total Range ($R$)** | $x(T) = v_{0x} \cdot T$ | **$979.7 \text{ m}$** |





# Time and Position arrays
t = np
