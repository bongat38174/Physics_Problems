# Task 08 – Work of a Variable Force

## Problem Statement

A one-dimensional force acts on a particle:

$$
F(x) = - k x
$$

* Write down the equation of motion and solve it.  
* Calculate work done from $0$ to $x_0$.  
* Interpret as potential energy.  
* Verify $F = -\frac{dU}{dx}$.  
* Draw graphs of $F(x)$ and $U(x)$.

---

## Theory

- Equation of motion (Newton's second law):

$$
m \frac{d^2 x}{dt^2} = F(x) = - k x
$$

- Work done:

$$
W = \int_0^{x_0} F(x) dx
$$

- Potential energy:

$$
U(x) = \frac{1}{2} k x^2
$$

- Relation:

$$
F(x) = - \frac{dU}{dx}
$$

---

## Step-by-Step Solution

### Step 1 — Equation of motion

$$
m \frac{d^2 x}{dt^2} + k x = 0
$$

> “This is a simple harmonic oscillator with solution:”

$$
x(t) = A \cos(\omega t) + B \sin(\omega t), \quad \omega = \sqrt{\frac{k}{m}}
$$

---

### Step 2 — Work done from 0 to $x_0$

$$
W = \int_0^{x_0} (-kx) dx = -\frac{1}{2} k x_0^2
$$

> “This equals minus the change in potential energy.”

---

### Step 3 — Potential energy

$$
U(x) = \frac{1}{2} k x^2
$$

> “And indeed, $F = - \frac{dU}{dx}$”

---

## Interpretation

> “The work done by the force is stored as potential energy. The force always acts to restore the particle to $x=0$.”
