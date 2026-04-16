# Vector Lorentz Force

## Problem

A proton moves with a velocity

$$
\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k}) , \text{m/s}
$$

in a region where the magnetic field is

$$
\vec{B} = (\hat{i} + 2\hat{j} - \hat{k}) , \text{T}.
$$

Find the magnitude of the magnetic force acting on the proton.

---

## Solution

The magnetic force is given by:

$$
\vec{F} = q , \vec{v} \times \vec{B}
$$

---

### Step 1: Convert to component form

$$
\vec{v} = (2, -4, 1), \quad \vec{B} = (1, 2, -1)
$$

---

### Step 2: Cross product

$$
\vec{v} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \
2 & -4 & 1 \
1 & 2 & -1
\end{vmatrix}
$$

$$
= (2, 3, 8)
$$

---

### Step 3: Magnitude

$$
|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2} = \sqrt{77}
$$

---

### Step 4: Multiply by charge

$$
q = 1.6 \times 10^{-19} , \text{C}
$$

$$
F = q |\vec{v} \times \vec{B}| = (1.6 \times 10^{-19}) \sqrt{77}
$$

$$
F \approx 1.4 \times 10^{-18} , \text{N}
$$

---

## Final Answer

$$
\boxed{1.4 \times 10^{-18} , \text{N}}
$$

---

## Key Insight

* Magnetic force is perpendicular to both velocity and magnetic field.
* Direction is given by the right-hand rule.
* Only magnitude is required here.
