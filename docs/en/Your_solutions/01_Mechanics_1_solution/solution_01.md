# Solutions goes here

..# Task 01 – Projectile Motion

## Problem Statement

A projectile is launched from the ground with an initial velocity

$v_0 = 100 \text{ m/s}$

at an angle

$\theta = 37^\circ$

above the horizontal. Air resistance is neglected.

Determine:

1. The differential equations of motion.
2. The time of flight.
3. The maximum height.
4. The horizontal range.

---

## Theory

Projectile motion in a uniform gravitational field is governed by Newton's second law.

The only force acting on the projectile is gravity

$$
\vec{F} = m\vec{g}
$$

which produces the acceleration

$$
\vec{a} = (0,-g)
$$

where

$$
g = 9.81 \text{ m/s}^2
$$

The motion can be separated into **independent horizontal and vertical components**.

---

## Step-by-Step Solution

### Initial Velocity Components

The initial velocity is decomposed into horizontal and vertical components:

$$
v_{0x} = v_0 \cos \theta
$$

$$
v_{0y} = v_0 \sin \theta
$$

Substituting the numerical values:

$$
v_{0x} = 100 \cos 37^\circ
$$

$$
v_{0y} = 100 \sin 37^\circ
$$

Using

$$
\cos 37^\circ \approx 0.798
$$

$$
\sin 37^\circ \approx 0.602
$$

we obtain

$$
v_{0x} \approx 79.8 \text{ m/s}
$$

$$
v_{0y} \approx 60.2 \text{ m/s}
$$

---

### Differential Equations of Motion

From Newton's second law:

Horizontal direction

$$
m\frac{d^2x}{dt^2} = 0
$$

which simplifies to

$$
\frac{d^2x}{dt^2} = 0
$$

Vertical direction

$$
m\frac{d^2y}{dt^2} = -mg
$$

which simplifies to

$$
\frac{d^2y}{dt^2} = -g
$$

---

### Velocity Functions

Integrating the accelerations:

Horizontal velocity

$$
v_x(t) = v_{0x}
$$

Vertical velocity

$$
v_y(t) = v_{0y} - gt
$$

---

### Position Functions

Integrating once more:

Horizontal position

$$
x(t) = v_{0x}t
$$

Vertical position

$$
y(t) = v_{0y}t - \frac{1}{2}gt^2
$$

---

### Time of Flight

The projectile returns to the ground when

$$
y(t) = 0
$$

Thus

$$
v_{0y}t - \frac{1}{2}gt^2 = 0
$$

Factoring:

$$
t(v_{0y} - \frac{1}{2}gt) = 0
$$

The non-trivial solution is

$$
t = \frac{2v_{0y}}{g}
$$

Substituting values:

$$
t = \frac{2(60.2)}{9.81}
$$

$$
t \approx 12.28 \text{ s}
$$

---

### Maximum Height

Maximum height occurs when the vertical velocity becomes zero:

$$
v_y = 0
$$

Thus

$$
v_{0y} - gt = 0
$$

$$
t_{max} = \frac{v_{0y}}{g}
$$

Substituting:

$$
t_{max} = \frac{60.2}{9.81}
$$

$$
t_{max} \approx 6.14 \text{ s}
$$

Now compute the height:

$$
H = v_{0y}t_{max} - \frac{1}{2}gt_{max}^2
$$

Substituting:

$$
H = 60.2(6.14) - \frac{1}{2}(9.81)(6.14)^2
$$

$$
H \approx 184.6 \text{ m}
$$

---

### Range

The horizontal range is

$$
R = v_{0x}T
$$

Substituting

$$
R = 79.8 \times 12.28
$$

$$
R \approx 980 \text{ m}
$$

---

## Final Result

Time of flight

$$
T \approx 12.28 \text{ s}
$$

Maximum height

$$
H \approx 184.6 \text{ m}
$$

Range

$$
R \approx 980 \text{ m}
$$

---

## Interpretation

The projectile follows a **parabolic trajectory** because horizontal motion is uniform while vertical motion is uniformly accelerated.

The symmetry of projectile motion implies:

- time to reach maximum height equals half the total flight time
- the trajectory is symmetric about the peak
- horizontal velocity remains constant throughout the motion..