Step 1: Understand the Given Data

We start with three main pieces of information:

Initial Velocity ($v_0$): $100 \text{ m/s}$ (The speed at the start)

Launch Angle ($\theta$): $37^\circ$ (The direction)

Gravity ($g$): $9.81 \text{ m/s}^2$ (The force pulling it down)

Step 2: Split the Velocity (Vector Components)

A projectile moves in two directions at the same time: Horizontal (Left-Right) and Vertical (Up-Down). We must calculate the starting speed for each:

Horizontal Velocity ($v_{0x}$):

$$v_{0x} = v_0 \cdot \cos(37^\circ) = 100 \cdot 0.8 \approx 80 \text{ m/s}$$

Vertical Velocity ($v_{0y}$):

$$v_{0y} = v_0 \cdot \sin(37^\circ) = 100 \cdot 0.6 \approx 60 \text{ m/s}$$

Step 3: Derive the Equations of Motion

We use Newton's Second Law. Since there is no air, only gravity matters.

1. Horizontal Direction ($x$):

There is no force pushing or pulling sideways. So, acceleration is zero ($a_x = 0$).

Velocity: It stays constant at $80 \text{ m/s}$.

Position: $x(t) = v_{0x} \cdot t = 80t$

2. Vertical Direction ($y$):

Gravity pulls the object down ($a_y = -9.81 \text{ m/s}^2$).

Velocity: It starts fast but slows down as it goes up.

$$v_y(t) = v_{0y} - gt = 60 - 9.81t$$

Position:

$$y(t) = v_{0y} \cdot t - \frac{1}{2}gt^2 = 60t - 4.9t^2$$

Step 4: Find the Time of Flight ($T$)

The object hits the ground when its height is zero ($y = 0$).

$$0 = 60T - 4.9T^2$$

We factor out $T$:

$$T(60 - 4.9T) = 0$$

This gives us $T = \frac{60}{4.9} \approx \mathbf{12.27 \text{ seconds}}$.

Step 5: Find the Maximum Height ($H_{max}$)

At the highest point, the object stops going up for a split second ($v_y = 0$).

$$v_y^2 = v_{0y}^2 - 2gH$$

$$0 = (60)^2 - 2 \cdot 9.81 \cdot H$$

$$H = \frac{3600}{19.62} \approx \mathbf{184.6 \text{ meters}}$$

Step 6: Find the Range ($R$)

The range is how far it travels horizontally before hitting the ground.

$$R = \text{Horizontal Speed} \times \text{Total Time}$$

$$R = 80 \text{ m/s} \times 12.27 \text{ s} \approx \mathbf{981.6 \text{ meters}}$$

Summary Table for Your Presentation

QuestionLogicResultHow long?When $y=0$$12.3 \text{ s}$How high?When $v_y=0$$184.6 \text{ m}$How far?$v_x \times \text{Time}$$981.6 \text{ m}$ 
