# ✅ **Solution 9: Vertical Throw with Drag**

---

## **Given:**

[
m\frac{dv}{dt} = -mg - kv
]
Initial conditions:
[
v(0)=v_0, \quad x(0)=10
]

---

## **1. Solve the differential equation**

Rearrange:
[
\frac{dv}{dt} = -g - \frac{k}{m}v
]

This is a first-order linear ODE:

[
\frac{dv}{dt} + \frac{k}{m}v = -g
]

---

### **Solution for velocity**

The solution is:

[
v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}
]

---

## **2. Position function**

Since:
[
v = \frac{dx}{dt}
]

Integrate:

[
x(t)=10 + \frac{m}{k}\left(v_0+\frac{mg}{k}\right)\left(1 - e^{-\frac{k}{m}t}\right) - \frac{mg}{k}t
]

---

## **3. Maximum height**

At maximum height:
[
v(t)=0
]

[
\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t} = \frac{mg}{k}
]

Solve for (t):

[
t = \frac{m}{k}\ln\left(\frac{v_0 + \frac{mg}{k}}{\frac{mg}{k}}\right)
]

Substitute into (x(t)) to get the maximum height.

---

## **4. Comparison (without drag)**

Without drag:
[
v(t)=v_0 - gt
]

[
h = \frac{v_0^2}{2g}
]

---

### **Key comparison:**

| Case         | Behavior                                |
| ------------ | --------------------------------------- |
| With drag    | Lower maximum height, exponential decay |
| Without drag | Higher height, symmetric motion         |

---

## **5. Numerical Simulation (Python idea)**

You can simulate using:

```python
import numpy as np
import matplotlib.pyplot as plt

m = 1
k = 0.5
g = 9.81
v0 = 10

t = np.linspace(0,5,100)

v = (v0 + m*g/k)*np.exp(-k/m*t) - m*g/k

plt.plot(t, v)
plt.xlabel("Time")
plt.ylabel("Velocity")
plt.title("Velocity with air resistance")
plt.show()
```

---

### ✅ **Final Answers Summary**

* Velocity:
  [
  v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}
  ]

* Position:
  [
  x(t)=10 + \frac{m}{k}\left(v_0+\frac{mg}{k}\right)(1-e^{-\frac{k}{m}t}) - \frac{mg}{k}t
  ]

* Drag reduces maximum height compared to no drag.

---


