# Task 09 – Vertical Throw with Drag

## Problem Statement

Equation of motion:

$$
m \frac{dv}{dt} = - mg - k v
$$

with initial conditions: $v(0) = v_0$, $x(0) = 10 \ \mathrm{m}$

* Solve analytically  
* Determine maximum height  
* Compare with no drag  
* Suggest numerical simulation

---

## Theory

> “This is a first-order linear differential equation with air resistance proportional to velocity.”

Rewriting:

$$
\frac{dv}{dt} + \frac{k}{m} v = - g
$$

> “We solve using integrating factor.”

---

## Step-by-Step Solution

### Step 1 — Solve differential equation

Integrating factor:

$$
\mu(t) = e^{\frac{k}{m} t}
$$

Solution:

$$
v(t) = (v_0 + \frac{mg}{k}) e^{-k t / m} - \frac{mg}{k}
$$

---

### Step 2 — Maximum height

> “Max height occurs when $v=0$”

Set:

$$
0 = (v_0 + \frac{mg}{k}) e^{-k t / m} - \frac{mg}{k}
$$

Solve for time:

$$
t_\text{max} = - \frac{m}{k} \ln \left( \frac{mg}{k v_0 + mg} \right)
$$

Substitute $t_\text{max}$ in

$$
x(t) = x_0 + \int_0^{t_\text{max}} v(t) dt
$$

> “This gives the maximum height, which is lower than without drag.”

---

### Step 3 — Comparison with no drag

- Without drag: $h_\text{max} = x_0 + \frac{v_0^2}{2 g}$  
- With drag: $h_\text{max} < x_0 + \frac{v_0^2}{2 g}$

---

## Interpretation

> “Air resistance reduces maximum height and slows ascent. The motion asymptotically approaches terminal velocity on descent.”

---

### Step 4 — Numerical simulation

> “Use Python or HTML to integrate $v(t)$ over time to simulate $x(t)$. This is useful for visualizing realistic projectile motion with drag.”
