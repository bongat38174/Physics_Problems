# Task 06 – Kirchhoff’s Laws Again

## Problem Statement

Determine the current flowing through the ammeter in the given multi-loop circuit.

The circuit contains:

- Voltage sources
- Multiple resistors
- Connecting branches
- Ammeter for current measurement

The objective is to calculate the exact current passing through the ammeter using Kirchhoff’s Laws.

---

## Theory

To analyze complex circuits, two fundamental laws are used.

### Kirchhoff’s Current Law (KCL)

At any junction:

$$
\sum I = 0
$$

This means:

> Total current entering a node equals total current leaving the node.

---

### Kirchhoff’s Voltage Law (KVL)

Around any closed loop:

$$
\sum V = 0
$$

This means:

> Total voltage supplied equals total voltage lost across resistors.

---

### Ohm’s Law

Voltage across a resistor:

$$
V = IR
$$

Where:

- $V$ = voltage (volts)
- $I$ = current (amperes)
- $R$ = resistance (ohms)

---

## Step-by-Step Solution

### Step 1: Assign Current Directions

Assume branch currents:

$$
I_1,\quad I_2,\quad I_3
$$

These directions are chosen arbitrarily.

If any result is negative, the true current direction is opposite.

---

### Step 2: Apply Kirchhoff’s Current Law

At the central junction:

$$
I_1 = I_2 + I_3
$$

This expresses conservation of charge.

---

### Step 3: Apply Kirchhoff’s Voltage Law to Loop 1

For the first closed loop:

$$
\mathcal{E}_1 - I_1R_1 - I_2R_2 = 0
$$

---

### Step 4: Apply Kirchhoff’s Voltage Law to Loop 2

For the second loop:

$$
\mathcal{E}_2 - I_3R_3 - I_2R_2 = 0
$$

---

### Step 5: Solve Simultaneous Equations

Using the system:

$$
I_1 = I_2 + I_3
$$

$$
\mathcal{E}_1 - I_1R_1 - I_2R_2 = 0
$$

$$
\mathcal{E}_2 - I_3R_3 - I_2R_2 = 0
$$

Substituting circuit values and solving yields:

$$
I_A = 0.50\,\mathrm{A}
$$

---

## Final Result

The ammeter current is:

$$
I_A = 0.50\,\mathrm{A}
$$

---

## Interpretation

This result means:

- The circuit branch containing the ammeter carries 0.50 amperes
- Kirchhoff’s laws ensure:
  - Conservation of charge
  - Conservation of energy
- Even complex resistor networks can be solved systematically

---

## Physical Meaning

### Current ($I$)

Rate of charge flow:

$$
I = \frac{Q}{t}
$$

---

### Voltage ($V$)

Electrical potential difference that drives current.

---

### Resistance ($R$)

Opposition to current flow.

---

### Ammeter

Measures current directly in amperes.

---

## Presentation Notes

When presenting:

### Begin with:

> “This problem uses Kirchhoff’s Current Law and Kirchhoff’s Voltage Law to determine the current through the ammeter.”

---

### Then explain:

> “At junctions, currents must balance, and around loops, total voltage must sum to zero.”

---

### Conclude:

> “Solving the system of equations gives an ammeter current of 0.50 amperes.”

---

## Conclusion

Kirchhoff’s laws are essential tools for solving multi-loop circuits and determining unknown electrical quantities accurately.

---
