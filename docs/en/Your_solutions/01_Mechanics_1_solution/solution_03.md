# Task 03 – Path Intersection

## Problem Statement

Alice moves according to

$$
A(t) = (2+t, 8-3t)
$$

Bob moves according to

$$
B(t) = (2t-1, 2t+2)
$$

Determine whether their paths intersect. If they do, determine the collision time and position.

---

## Theory

Two moving objects collide if their **positions are equal at the same time**.

Thus the following system must be satisfied:

$$
x_A(t) = x_B(t)
$$

$$
y_A(t) = y_B(t)
$$

---

## Step-by-Step Solution

### X-coordinate equality

$$
2+t = 2t-1
$$

Solving for $t$

$$
t = 3
$$

### Y-coordinate equality

Substitute into the second equation

$$
8 - 3t = 2t + 2
$$

Substitute $t=3$

$$
8 - 9 = 6 + 2
$$

$$
-1 \neq 8
$$

The equality is not satisfied.

---

### Minimum Distance

Distance between the two points

$$
d(t) =
\sqrt{(x_A-x_B)^2 + (y_A-y_B)^2}
$$

Substitute coordinates:

$$
d(t) =
\sqrt{(2+t-(2t-1))^2 + (8-3t-(2t+2))^2}
$$

Simplify

$$
d(t)=
\sqrt{(3-t)^2 + (6-5t)^2}
$$

The minimum distance occurs when the derivative of $d(t)$ is zero.

---

## Final Result

The two paths **do not intersect**, therefore Alice and Bob never collide.

---

## Interpretation

Even though the trajectories cross geometrically, the two individuals reach those points at **different times**, preventing a collision.