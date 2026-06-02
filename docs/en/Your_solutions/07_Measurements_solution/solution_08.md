# 8. Mass-Spring Measurements

## Theory

The period of oscillation for a mass attached to a spring is given by:

\[
T = 2\pi\sqrt{\frac{m}{k}}
\]

where:

- \(T\) = period of oscillation (s)
- \(m\) = mass (kg)
- \(k\) = spring constant (N/m)

Rearranging the equation to solve for the spring constant:

\[
k = \frac{4\pi^2m}{T^2}
\]

---

## Example Experiment

Assume:

\[
m = 0.500\ \text{kg}
\]

The following times were measured for **10 complete oscillations**:

| Trial | Time for 10 Oscillations (s) |
|---------|---------|
| 1 | 14.15 |
| 2 | 14.05 |
| 3 | 14.20 |
| 4 | 14.10 |
| 5 | 14.12 |
| 6 | 14.08 |
| 7 | 14.17 |
| 8 | 14.09 |
| 9 | 14.14 |
| 10 | 14.11 |

---

## Step 1: Calculate the Mean Time

The mean is:

\[
\bar{t} = \frac{\sum t_i}{N}
\]

Adding all measurements:

\[
14.15+14.05+14.20+14.10+14.12+14.08+14.17+14.09+14.14+14.11
\]

\[
=141.21\ \text{s}
\]

Therefore:

\[
\bar{t}
=
\frac{141.21}{10}
=
14.121\ \text{s}
\]

---

## Step 2: Calculate the Mean Period

Since each measurement corresponds to 10 oscillations:

\[
T=\frac{\bar{t}}{10}
\]

\[
T=\frac{14.121}{10}
\]

\[
T=1.4121\ \text{s}
\]

---

## Step 3: Calculate the Standard Deviation

Using:

\[
s=\sqrt{\frac{1}{N-1}\sum (t_i-\bar{t})^2}
\]

The standard deviation of the timing measurements is:

\[
s_t \approx 0.047\ \text{s}
\]

Since the measurements were for 10 oscillations:

\[
s_T=\frac{s_t}{10}
\]

\[
s_T=0.0047\ \text{s}
\]

---

## Step 4: Calculate the Spring Constant

Using:

\[
k=\frac{4\pi^2m}{T^2}
\]

Substituting values:

\[
k
=
\frac{4\pi^2(0.500)}
     {(1.4121)^2}
\]

\[
k
=
9.90\ \text{N/m}
\]

---

## Step 5: Calculate the Uncertainty in \(k\)

Because:

\[
k \propto T^{-2}
\]

the relative uncertainty is:

\[
\frac{\Delta k}{k}
=
2\frac{\Delta T}{T}
\]

Substituting values:

\[
\frac{\Delta k}{k}
=
2\left(\frac{0.0047}{1.4121}\right)
\]

\[
=0.0067
\]

Therefore:

\[
\Delta k
=
9.90(0.0067)
\]

\[
\Delta k
=
0.07\ \text{N/m}
\]

---

## Final Answer

\[
\boxed{
k=(9.90 \pm 0.07)\ \text{N/m}
}
\]

### Conclusion

The experimental spring constant is:

\[
\boxed{
k=(9.90 \pm 0.07)\ \text{N/m}
}
\]

The uncertainty is small, indicating that the timing measurements were reasonably consistent.