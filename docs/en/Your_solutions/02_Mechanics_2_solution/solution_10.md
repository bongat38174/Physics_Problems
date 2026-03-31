# Task 10 – Force Field and Power

## Problem Statement

A particle of mass $m=0.5 \ \mathrm{kg}$ moves in a force field with the trajectory:

$$
x = 5t^2 - t, \quad y = 2t^3, \quad z = -3t + 2
$$

Determine:

- The velocity of the particle  
- The momentum  
- The acceleration  
- The force acting on the particle  
- The power delivered by the field

---

## Theory

Key concepts:

1. **Velocity**: derivative of position

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = \left(\frac{dx}{dt}, \frac{dy}{dt}, \frac{dz}{dt}\right)
$$

2. **Momentum**:

$$
\vec{p}(t) = m \vec{v}(t)
$$

3. **Acceleration**:

$$
\vec{a}(t) = \frac{d\vec{v}}{dt}
$$

4. **Force**:

$$
\vec{F}(t) = m \vec{a}(t)
$$

5. **Power**:

$$
P(t) = \vec{F} \cdot \vec{v}
$$

---

## Step-by-Step Solution

### Step 1 — Velocity

Compute derivatives:

$$
v_x = \frac{dx}{dt} = 10t - 1
$$

$$
v_y = \frac{dy}{dt} = 6 t^2
$$

$$
v_z = \frac{dz}{dt} = -3
$$

So the velocity vector is:

$$
\vec{v}(t) = (10t -1, 6t^2, -3)
$$

---

### Step 2 — Momentum

$$
\vec{p}(t) = m \vec{v}(t) = 0.5 (10t-1, 6t^2, -3)
$$

$$
\vec{p}(t) = (5t - 0.5, 3 t^2, -1.5) \ \mathrm{kg \cdot m/s}
$$

---

### Step 3 — Acceleration

$$
a_x = \frac{dv_x}{dt} = 10
$$

$$
a_y = \frac{dv_y}{dt} = 12 t
$$

$$
a_z = \frac{dv_z}{dt} = 0
$$

$$
\vec{a}(t) = (10, 12 t, 0)
$$

---

### Step 4 — Force

$$
\vec{F}(t) = m \vec{a}(t) = 0.5 (10, 12 t, 0)
$$

$$
\vec{F}(t) = (5, 6 t, 0) \ \mathrm{N}
$$

---

### Step 5 — Power

$$
P(t) = \vec{F} \cdot \vec{v} = 5(10t-1) + (6t)(6 t^2) + 0(-3)
$$

$$
P(t) = 50 t - 5 + 36 t^3
$$

$$
P(t) = 36 t^3 + 50 t - 5 \ \mathrm{W}
$$

---

## Final Result

- **Velocity**: $\vec{v}(t) = (10t -1, 6t^2, -3)$  
- **Momentum**: $\vec{p}(t) = (5t - 0.5, 3 t^2, -1.5) \ \mathrm{kg \cdot m/s}$  
- **Acceleration**: $\vec{a}(t) = (10, 12 t, 0)$  
- **Force**: $\vec{F}(t) = (5, 6 t, 0) \ \mathrm{N}$  
- **Power**: $P(t) = 36 t^3 + 50 t - 5 \ \mathrm{W}$

---

## Interpretation

> “Velocity and acceleration vary in time. The force acting on the particle changes with time, producing a time-dependent power. Positive power corresponds to energy added to the particle; negative power corresponds to energy extracted.”
