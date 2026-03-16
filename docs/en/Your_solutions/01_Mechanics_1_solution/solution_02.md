# Task 02 – Range Optimization

## Problem Statement

For projectile motion with initial velocity $v_0$, the horizontal range is

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

Show analytically that the range is maximized when

$$
\theta = 45^\circ
$$

---

## Theory

The horizontal range of a projectile launched from ground level is obtained from the kinematic equations of motion.

The general expression for the range is

$$
R(\theta) = \frac{v_0^2}{g}\sin(2\theta)
$$

To determine the launch angle that maximizes the range, the derivative of the range with respect to $\theta$ is set equal to zero.

---

## Step-by-Step Solution

The function to be maximized is

$$
R(\theta) = \frac{v_0^2}{g}\sin(2\theta)
$$

Differentiate with respect to $\theta$.

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta)
$$

For an extremum

$$
\frac{dR}{d\theta} = 0
$$

Thus

$$
2\cos(2\theta) = 0
$$

which gives

$$
\cos(2\theta) = 0
$$

The cosine function is zero when

$$
2\theta = 90^\circ
$$

Therefore

$$
\theta = 45^\circ
$$

---

## Final Result

The projectile achieves **maximum horizontal range** when

$$
\theta = 45^\circ
$$

---

## Interpretation

The result follows from the trigonometric identity that $\sin(2\theta)$ reaches its maximum value of 1 when

$$
2\theta = 90^\circ
$$

Thus projectile motion produces the greatest horizontal distance when the vertical and horizontal velocity components are equal.