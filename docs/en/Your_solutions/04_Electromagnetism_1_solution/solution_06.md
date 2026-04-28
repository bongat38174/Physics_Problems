# Task 06 – Electric Field from a System of Charges

## Problem Statement

Two point charges are placed on the x-axis:

- $+q$ at $(-a, 0)$  
- $+2q$ at $(a, 0)$  

Tasks:

1. Determine the electric field $\vec{E}(0, y)$, $\vec{E}(x, 0)$, and general $\vec{E}(x, y)$.  
2. Determine conditions for $E_x = 0$, $E_y = 0$, and $\vec{E} = 0$.  
3. Calculate the field for $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$.  
4. Investigate the limit $y \gg a$.  

---

## Theory

Electric field due to a point charge:

$$
\vec{E} = k \frac{q}{r^3} \vec{r}
$$

where $\vec{r}$ is the vector from the charge to the observation point.

---

## Step-by-Step Solution

### 1. General Field $\vec{E}(x, y)$

Position vectors from charges:

From $+q$ at $(-a,0)$:

$$
\vec{r}_1 = (x+a, y)
$$

From $+2q$ at $(a,0)$:

$$
\vec{r}_2 = (x-a, y)
$$

Distances:

$$
r_1 = \sqrt{(x+a)^2 + y^2}
$$

$$
r_2 = \sqrt{(x-a)^2 + y^2}
$$

Electric fields:

$$
\vec{E}_1 = k \frac{q}{r_1^3}(x+a, y)
$$

$$
\vec{E}_2 = k \frac{2q}{r_2^3}(x-a, y)
$$

Total field:

$$
\vec{E}(x,y) = \vec{E}_1 + \vec{E}_2
$$

---

### 2. Field on the y-axis $\vec{E}(0,y)$

Substitute $x=0$:

$$
r_1 = r_2 = \sqrt{a^2 + y^2}
$$

Field components:

$$
E_x = k \frac{q a}{(a^2+y^2)^{3/2}} - k \frac{2q a}{(a^2+y^2)^{3/2}}
$$

$$
E_x = - k \frac{q a}{(a^2+y^2)^{3/2}}
$$

$$
E_y = k \frac{q y}{(a^2+y^2)^{3/2}} + k \frac{2q y}{(a^2+y^2)^{3/2}}
$$

$$
E_y = k \frac{3q y}{(a^2+y^2)^{3/2}}
$$

---

### 3. Field on the x-axis $\vec{E}(x,0)$

Set $y=0$:

$$
E_x = k \frac{q}{(x+a)^2} + k \frac{2q}{(x-a)^2}
$$

Direction depends on position relative to charges.

---

### 4. Condition for Zero Field

For equilibrium:

$$
E_x = 0
$$

Between charges:

$$
\frac{q}{(x+a)^2} = \frac{2q}{(x-a)^2}
$$

Solve:

$$
(x-a)^2 = 2(x+a)^2
$$

Taking square root:

$$
x-a = \sqrt{2}(x+a)
$$

Solve:

$$
x = \frac{a(1+\sqrt{2})}{1-\sqrt{2}}
$$

---

### 5. Numerical Calculation

Given:

$$
a = 0.2 \ \mathrm{m}, \quad y = 0.3 \ \mathrm{m}, \quad q = 2\times10^{-6} \ \mathrm{C}
$$

$$
k = 9\times10^9
$$

Compute denominator:

$$
(a^2 + y^2)^{3/2} = (0.04 + 0.09)^{3/2}
$$

$$
= (0.13)^{3/2} \approx 0.0469
$$

---

### Compute $E_x$

$$
E_x = - \frac{(9\times10^9)(2\times10^{-6})(0.2)}{0.0469}
$$

$$
E_x \approx -7.68 \times 10^4 \ \mathrm{N/C}
$$

---

### Compute $E_y$

$$
E_y = \frac{(9\times10^9)(3 \cdot 2\times10^{-6})(0.3)}{0.0469}
$$

$$
E_y \approx 3.45 \times 10^5 \ \mathrm{N/C}
$$

---

### Resulting field

$$
\vec{E} \approx (-7.68\times10^4, \ 3.45\times10^5) \ \mathrm{N/C}
$$

---

### 6. Limit $y \gg a$

When $y$ is much larger than $a$:

$$
r \approx y
$$

Total charge:

$$
q_{\text{total}} = q + 2q = 3q
$$

Thus:

$$
E \approx k \frac{3q}{y^2}
$$

---

## Final Result

- General field: vector sum of both charges  
- Numerical field:

$$
\vec{E} \approx (-7.68\times10^4, \ 3.45\times10^5) \ \mathrm{N/C}
$$

- Far field:

$$
E \approx k \frac{3q}{y^2}
$$

---

## Interpretation

The electric field is the vector sum of contributions from both charges.  
Closer charge contributes more strongly.  
At large distances, the system behaves like a single charge of $3q$.
