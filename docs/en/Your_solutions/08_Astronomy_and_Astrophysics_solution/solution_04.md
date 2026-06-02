# Problem 4 – Geostationary Orbit

## Problem Statement

A geostationary satellite remains above the same point on Earth at all times.

Determine:

1. The required orbital period.
2. The altitude of the geostationary orbit above Earth's surface.

---

## Given Data

Earth's radius:

$$
R_E = 6378\ \text{km}
$$

Earth's mass:

$$
M_E = 5.97\times10^{24}\ \text{kg}
$$

Gravitational constant:

$$
G = 6.674\times10^{-11}
\ \text{N m}^2/\text{kg}^2
$$

Earth's rotation period:

$$
T = 24\ \text{hours}
$$

Convert to seconds:

$$
T = 24\times3600
$$

$$
T = 86400\ \text{s}
$$

---

# Theory

A geostationary satellite must orbit Earth with the same period as Earth's rotation.

Therefore:

$$
T_{orbit}=24\ \text{hours}
$$

To find the orbital radius, use:

$$
T=
2\pi
\sqrt{
\frac{r^3}{GM_E}
}
$$

Rearrange:

$$
r^3=
\frac{
GM_ET^2
}{
4\pi^2
}
$$

Thus:

$$
r=
\sqrt[3]{
\frac{
GM_ET^2
}{
4\pi^2
}
}
$$

---

# Step 1: Calculate GM

$$
GM_E=
(6.674\times10^{-11})
(5.97\times10^{24})
$$

$$
GM_E
=
3.986\times10^{14}
$$

---

# Step 2: Calculate Numerator

$$
GM_ET^2
=
(3.986\times10^{14})
(86400)^2
$$

$$
=
2.975\times10^{24}
$$

---

# Step 3: Divide by \(4\pi^2\)

$$
4\pi^2
=
39.478
$$

Therefore:

$$
\frac{
2.975\times10^{24}
}{
39.478
}
=
7.536\times10^{22}
$$

---

# Step 4: Take Cube Root

$$
r=
\sqrt[3]{
7.536\times10^{22}
}
$$

$$
r
=
4.216\times10^{7}
\ \text{m}
$$

Convert to kilometers:

$$
r
=
42160\ \text{km}
$$

---

# Step 5: Calculate Altitude

Altitude is measured above Earth's surface:

$$
h=r-R_E
$$

Substitute values:

$$
h=
42160-6378
$$

$$
h=
35782\ \text{km}
$$

---

# Final Answers

### Orbital Period

$$
\boxed{
T=24\ \text{hours}
}
$$

---

### Orbital Radius

$$
\boxed{
r=42160\ \text{km}
}
$$

---

### Altitude Above Earth

$$
\boxed{
h\approx35782\ \text{km}
}
$$

---

# Why Geostationary Satellites Are Useful

Because the satellite takes exactly 24 hours to complete one orbit, it rotates together with Earth.

As a result:

- It always appears fixed in the sky.
- Ground antennas do not need to move.
- Communication signals remain continuous.

This is why geostationary satellites are commonly used for:

- Television broadcasting
- Weather monitoring
- Telecommunications
- Internet services

---

# Meaning of Symbols

| Symbol | Meaning |
|----------|----------|
| $T$ | Orbital period |
| $r$ | Distance from Earth's center |
| $h$ | Altitude above Earth |
| $G$ | Gravitational constant |
| $M_E$ | Earth's mass |
| $R_E$ | Earth's radius |

---

# Physical Interpretation

A satellite in low Earth orbit completes an orbit in about 90 minutes.

A geostationary satellite must move much farther away from Earth so that gravity weakens enough to allow a 24-hour orbit.

This distance is approximately:

$$
35782\ \text{km}
$$

above Earth's surface.

---

# Presentation Script

> In this problem, we determine the altitude of a geostationary satellite.
>
> A geostationary satellite must remain above the same point on Earth, so its orbital period must equal Earth's rotation period, which is 24 hours.
>
> Using the orbital period equation, we calculate the orbital radius and obtain approximately 42,160 kilometers from Earth's center.
>
> To find the altitude above Earth's surface, we subtract Earth's radius.
>
> This gives approximately 35,782 kilometers.
>
> Therefore, a geostationary satellite must orbit at an altitude of about 35,800 kilometers and complete one orbit every 24 hours.
