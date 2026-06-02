# 9. Pendulum Measurements

## Theory

The period of a simple pendulum is given by:

\[
T = 2\pi\sqrt{\frac{L}{g}}
\]

where:

- \(T\) = period of oscillation (s)
- \(L\) = pendulum length (m)
- \(g\) = acceleration due to gravity (m/s²)

Rearranging the formula to solve for \(g\):

\[
g = \frac{4\pi^2L}{T^2}
\]

---

## Experimental Data

Assume the pendulum length is measured exactly as:

\[
L = 1.00\ \text{m}
\]

Ten measurements were taken for the time of **10 complete oscillations**.

| Trial | Time for 10 Oscillations (s) |
|---------|---------|
| 1 | 20.02 |
| 2 | 20.18 |
| 3 | 20.07 |
| 4 | 19.95 |
| 5 | 20.11 |
| 6 | 20.05 |
| 7 | 20.09 |
| 8 | 20.13 |
| 9 | 20.00 |
| 10 | 20.10 |

---

## Step 1: Calculate the Mean Time

The mean is:

\[
\bar{t}=\frac{\sum t_i}{N}
\]

Sum of all measurements:

\[
20.02+20.18+20.07+19.95+20.11+20.05+20.09+20.13+20.00+20.10
\]

\[
=200.70\ \text{s}
\]

Therefore:

\[
\bar{t}
=
\frac{200.70}{10}
=
20.07\ \text{s}
\]

---

## Step 2: Calculate the Mean Period

Each measurement corresponds to 10 oscillations.

Therefore:

\[
T=\frac{\bar{t}}{10}
\]

\[
T=\frac{20.07}{10}
\]

\[
T=2.007\ \text{s}
\]

---

## Step 3: Calculate the Standard Deviation

The sample standard deviation is:

\[
s=\sqrt{\frac{1}{N-1}\sum (t_i-\bar{t})^2}
\]

Using the measured data:

\[
s_t \approx 0.069\ \text{s}
\]

Since the measurements were taken for 10 oscillations:

\[
s_T=\frac{s_t}{10}
\]

\[
s_T=0.0069\ \text{s}
\]

---

## Step 4: Calculate the Acceleration Due to Gravity

Using:

\[
g=\frac{4\pi^2L}{T^2}
\]

Substituting values:

\[
g
=
\frac{4\pi^2(1.00)}
     {(2.007)^2}
\]

\[
g
=
9.80\ \text{m/s}^2
\]

---

## Step 5: Calculate the Uncertainty in \(g\)

Because:

\[
g\propto T^{-2}
\]

the relative uncertainty is:

\[
\frac{\Delta g}{g}
=
2\frac{\Delta T}{T}
\]

Substituting values:

\[
\frac{\Delta g}{g}
=
2\left(\frac{0.0069}{2.007}\right)
\]

\[
=0.0069
\]

Therefore:

\[
\Delta g
=
9.80(0.0069)
\]

\[
\Delta g
=
0.07\ \text{m/s}^2
\]

---

## Final Answer

\[
\boxed{
g=(9.80 \pm 0.07)\ \text{m/s}^2
}
\]

---

## Comparison with the Accepted Value

The accepted value of gravitational acceleration near Earth's surface is:

\[
g_{accepted}=9.81\ \text{m/s}^2
\]

Difference:

\[
|9.81-9.80|
=
0.01\ \text{m/s}^2
\]

The experimental result is extremely close to the accepted value and falls well within the calculated uncertainty.

---

## Conclusion

Using the measured oscillation times of a simple pendulum:

\[
\boxed{
g=(9.80 \pm 0.07)\ \text{m/s}^2
}
\]

The experiment demonstrates how the acceleration due to gravity can be determined accurately using only a pendulum and a stopwatch.