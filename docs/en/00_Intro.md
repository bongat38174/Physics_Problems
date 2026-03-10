# Section 0: Mathematical Foundations
I'll help you understand and solve the content in that document. Let me fetch it first.Perfect! I have the physics/math problems from the file. Here are the **solutions and explanations** for all 10 problems in Section 0: Mathematical Foundations:

---

## **1. Vector Algebra**
**Given:** $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

**a) Magnitude of each vector:**
- $|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} \approx 3.74$
- $|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21} \approx 4.58$

**b) Dot product:**
- $\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3$

**c) Cross product:**
- $\vec{a} \times \vec{b} = \begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$
- $= \vec{i}(1 \cdot 1 - (-3)(-2)) - \vec{j}(2 \cdot 1 - (-3)(4)) + \vec{k}(2(-2) - 1 \cdot 4)$
- $= \vec{i}(1 - 6) - \vec{j}(2 + 12) + \vec{k}(-4 - 4) = [-5, -14, -8]$

**d) Angle between vectors:**
- $\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|} = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}} \approx 0.175$
- $\theta = \arccos(0.175) \approx 79.9°$

---

## **2. Systems of Equations**
**Equations:** $2x + 3y = 12$ and $x - y = 1$

From the second equation: $x = y + 1$

Substitute into the first: $2(y + 1) + 3y = 12$
- $2y + 2 + 3y = 12$
- $5y = 10$
- $y = 2$, so $x = 3$

**Answer: $x = 3, y = 2$**

---

## **3. Proportionality (Gravitation)**
**Formula:** $F = G \frac{m_1 m_2}{r^2}$

If $r$ is doubled ($r' = 2r$) and both masses are halved ($m_1' = \frac{m_1}{2}$, $m_2' = \frac{m_2}{2}$):

$F' = G \frac{(\frac{m_1}{2})(\frac{m_2}{2}))(2r)^2} = G \frac{\frac{m_1 m_2}{4}}{4r^2} = \frac{1}{16} \cdot G\frac{m_1 m_2}{r^2} = \frac{F}{16}$

**Answer: The force decreases by a factor of 16 (becomes 1/16 of the original)**

---

## **4. Rearranging Formulas**
**Formula:** $T = 2\pi \sqrt{\frac{L}{g}}$

Solving for $g$:
- $T = 2\pi \sqrt{\frac{L}{g}}$
- $\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$
- $\frac{T^2}{4\pi^2} = \frac{L}{g}$
- $g = \frac{4\pi^2 L}{T^2}$

---

## **5. Trigonometry**
**Given:** $|\vec{A}| = 15$, $\theta = 60°$

- **Horizontal component:** $A_x = 15 \cos(60°) = 15 \cdot 0.5 = 7.5$
- **Vertical component:** $A_y = 15 \sin(60°) = 15 \cdot \frac{\sqrt{3}}{2} \approx 13.0$

---

## **6. Function Analysis**
**Function:** $f(x) = 3x^2 - 12x + 7$

Find critical points: $f'(x) = 6x - 12 = 0$
- $x = 2$

Check second derivative: $f''(x) = 6 > 0$ (concave up)
- **Local minimum** at $x = 2$: $f(2) = 3(4) - 12(2) + 7 = 12 - 24 + 7 = -5$
- **No local maximum**

---

## **7. Logic & Series**
**Setup:** Bicycle 10 m from wall, moving at 1 m/s; fly flying at 2 m/s

The fly flies until the bicycle reaches the wall. The bicycle takes $\frac{10 \text{ m}}{1 \text{ m/s}} = 10$ seconds to reach the wall.

During this time, the fly is constantly moving at 2 m/s.

**Total distance fly travels:** $2 \text{ m/s} \times 10 \text{ s} = 20$ meters

---

## **8. Definite Integrals**
**Integral:** $\int_0^{\pi} \sin(x) \, dx$

- $\int \sin(x) \, dx = -\cos(x) + C$
- $\int_0^{\pi} \sin(x) \, dx = [-\cos(x)]_0^{\pi} = -\cos(\pi) - (-\cos(0)) = -(-1) + 1 = 2$

**Answer: Area = 2 square units**

---

## **9. Optimization Problem**
**Constraint:** Rectangle under $y = 3 - x^2$ in the first quadrant

Let the rectangle have corners at $(0,0)$ and $(x, 3-x^2)$.
- **Area:** $A(x) = x(3 - x^2) = 3x - x^3$

Find critical points: $A'(x) = 3 - 3x^2 = 0$
- $x^2 = 1$, so $x = 1$ (positive solution)

Check: $A''(x) = -6x = -6 < 0$ at $x=1$ (maximum)

- **Width:** $x = 1$
- **Height:** $y = 3 - 1^2 = 2$
- **Maximum area:** $1 \times 2 = 2$ square units

---

## **10. Infinite Series**
**Pattern:** 1 m east, 1/2 m north, 1/3 m west, 1/4 m south, 1/5 m east, ...

Break into components:
- **x-direction:** $1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + ... = \sum_{n=0}^{\infty} \frac{(-1)^n}{2n+1} = \frac{\pi}{4}$ (Leibniz formula)
- **y-direction:** $\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + ... = \sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{2n} = \frac{\ln(2)}{2}$

**Final position:** $\left(\frac{\pi}{4}, \frac{\ln(2)}{2}\right) \approx (0.785, 0.347)$ meters

---

This covers all 10 problems with clear solutions and explanations ready for your presentation! 📊
## 1. Vector Algebra

Given two vectors in 3D space: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$. Calculate:

a) The magnitude of each vector.

b) The dot product $\vec{a} \cdot \vec{b}$.

c) The cross product $\vec{a} \times \vec{b}$.

d) The angle between vectors $\vec{a}$ and $\vec{b}$.

## 2. Systems of Equations

Find the values of $x$ and $y$ that satisfy both equations: $2x + 3y = 12$ and $x - y = 1$.

## 3. Proportionality

Consider the Universal Law of Gravitation: $F = G \frac{m_1 m_2}{r^2}$, where $F$ is the gravitational force between two masses $m_1$ and $m_2$, $r$ is the distance between their centers, and $G$ is the gravitational constant. Determine the factor by which the force $F$ changes if the distance $r$ is *doubled* and both masses ($m_1$ and $m_2$) are *halved*.

## 4. Rearranging Formulas

The formula for the period of a simple pendulum is $T = 2\pi \sqrt{\frac{L}{g}}$. Rearrange the equation give a formula for $g$ (acceleration due to gravity).

## 5. Trigonometry

A vector $\vec{A}$ has a magnitude of $15$ and makes an angle of $\theta = 60^\circ$ with the horizontal axis. Calculate its horizontal and vertical components.

## 6. Function Analysis

Consider the function $f(x) = 3x^2 - 12x + 7$. Identify any local maxima or minima.

## 7. Logic & Series

A bicycle is 10 meters from a wall and moves towards it at a constant speed of $1\text{ m/s}$. A fly starts from the bicycle's front wheel and flies towards the wall at $2\text{ m/s}$. When it hits the wall, it instantly turns back and flies to the bicycle, and so on. What is the total distance the fly travels before being crushed?

## 8. Definite Integrals

Calculate the area under the curve of the function $f(x) = \sin(x)$ from $x=0$ to $x=\pi$.

## 9. Optimization Problem

A rectangle is under the curve $y = 3 - x^2$ in the first quadrant. What are the dimensions of the rectangle with the maximum area?

## 10. Infinite Series

Determine the final position of an ant that starts at the origin and moves according to the following pattern: 1 m east, 1/2 m north, 1/3 m west, 1/4 m south, 1/5 m east, and so on.
