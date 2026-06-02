# Problem 2 – Orbital Mechanics

## Problem Statement

The International Space Station (ISS) orbits Earth at an altitude of approximately:

$$
h = 400\ \text{km}
$$

Earth's radius:

$$
R_E = 6378\ \text{km}
$$

Earth's mass:

$$
M_E = 5.97\times10^{24}\ \text{kg}
$$

Determine:

1. The orbital speed of the ISS.
2. Earth's orbital speed around the Sun.
3. Which moves faster:
   - the ISS around Earth,
   - or Earth around the Sun?

---

## Theory

For a circular orbit:

$$
v=\sqrt{\frac{GM}{r}}
$$

where:

- $v$ = orbital speed
- $G$ = gravitational constant
- $M$ = mass of central body
- $r$ = orbital radius

---

## Constants

Gravitational constant:

$$
G=6.674\times10^{-11}\ \text{N m}^2/\text{kg}^2
$$

---

# Part A – ISS Orbital Speed

## Step 1: Determine Orbital Radius

The ISS is 400 km above Earth.

Therefore:

$$
r=R_E+h
$$

Substitute:

$$
r=6378+400
$$

$$
r=6778\ \text{km}
$$

Convert to meters:

$$
r=6.778\times10^6\ \text{m}
$$

---

## Step 2: Apply Orbital Velocity Formula

$$
v=\sqrt{\frac{GM_E}{r}}
$$

Substitute values:

$$
v=
\sqrt{
\frac{
(6.674\times10^{-11})
(5.97\times10^{24})
}{
6.778\times10^6
}
}
$$

---

## Step 3: Simplify

First calculate:

$$
GM_E
=
3.986\times10^{14}
$$

Then:

$$
\frac{GM_E}{r}
=
5.88\times10^7
$$

Therefore:

$$
v=
\sqrt{5.88\times10^7}
$$

$$
v\approx7668\ \text{m/s}
$$

---

## ISS Speed

$$
\boxed{
v_{ISS}
\approx7.67\ \text{km/s}
}
$$

---

# Part B – Earth's Orbital Speed Around the Sun

## Given

Earth-Sun distance:

$$
r=150\times10^6\ \text{km}
$$

Convert:

$$
r=1.5\times10^{11}\ \text{m}
$$

Earth's orbital period:

$$
T=365.25\ \text{days}
$$

---

## Step 1: Convert Period to Seconds

$$
T
=
365.25\times24\times3600
$$

$$
T
=
3.156\times10^7\ \text{s}
$$

---

## Step 2: Calculate Orbit Circumference

$$
C=2\pi r
$$

$$
C
=
2\pi(1.5\times10^{11})
$$

$$
C
=
9.425\times10^{11}\ \text{m}
$$

---

## Step 3: Calculate Speed

$$
v=\frac{C}{T}
$$

Substitute:

$$
v=
\frac{
9.425\times10^{11}
}{
3.156\times10^7
}
$$

$$
v
=
2.99\times10^4\ \text{m/s}
$$

---

## Earth's Orbital Speed

$$
\boxed{
v_E
\approx29.9\ \text{km/s}
}
$$

---

# Comparison

ISS speed:

$$
7.67\ \text{km/s}
$$

Earth around Sun:

$$
29.9\ \text{km/s}
$$

---

## Ratio

$$
\frac{29.9}{7.67}
=
3.90
$$

---

## Final Answer

### ISS Orbital Speed

$$
\boxed{
7.67\ \text{km/s}
}
$$

---

### Earth's Orbital Speed Around Sun

$$
\boxed{
29.9\ \text{km/s}
}
$$

---

### Which is Faster?

$$
\boxed{
\text{Earth moves faster around the Sun}
}
$$

Earth's orbital speed is nearly four times larger than the ISS orbital speed.

---

# Physical Interpretation

The ISS travels very fast because it must continuously fall around Earth.

However, Earth travels even faster around the Sun because the Sun's gravitational influence extends over a much larger orbit.

---

# Meaning of Symbols

| Symbol | Meaning |
|----------|----------|
| $v$ | Orbital speed |
| $G$ | Gravitational constant |
| $M_E$ | Mass of Earth |
| $r$ | Orbital radius |
| $R_E$ | Radius of Earth |
| $h$ | ISS altitude |
| $C$ | Orbit circumference |
| $T$ | Orbital period |

---

# Presentation Script

> In this problem, we calculate the orbital speed of the International Space Station and compare it with Earth's orbital speed around the Sun.
>
> First, we determine the orbital radius by adding Earth's radius and the ISS altitude.
>
> Using the orbital velocity formula, we obtain a speed of approximately 7.67 kilometers per second.
>
> Next, we calculate Earth's orbital speed around the Sun by dividing the circumference of Earth's orbit by its orbital period.
>
> This gives approximately 29.9 kilometers per second.
>
> Comparing the two values, we find that Earth moves almost four times faster around the Sun than the ISS moves around Earth.s