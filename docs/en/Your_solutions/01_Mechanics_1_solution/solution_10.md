# Task 10 – Kinematics in Three Dimensions

## Problem Statement

The position vector is

$$
\vec r(t) =
(a\cos(\omega t),
b\sin(\omega t),
bt)
$$

---

## Step-by-Step Solution

### Trajectory Equation

From

$$
x=a\cos(\omega t)
$$

$$
y=b\sin(\omega t)
$$

Squaring

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

Thus the projection in the xy-plane is an **ellipse**.

Because

$$
z=bt
$$

the motion forms a **helical trajectory**.

---

### Path Length

Speed

$$
|\vec v| =
\sqrt{a^2\omega^2\sin^2(\omega t)+b^2\omega^2\cos^2(\omega t)+b^2}
$$

Path length

$$
s=\int_0^{t_0} |\vec v| dt
$$

---

### Python Visualization

```python
import numpy as np
import matplotlib.pyplot as plt

a=3
b=2
w=1

t=np.linspace(0,10,1000)

x=a*np.cos(w*t)
y=b*np.sin(w*t)
z=b*t

fig=plt.figure()
ax=fig.add_subplot(projection='3d')
ax.plot(x,y,z)
plt.show()