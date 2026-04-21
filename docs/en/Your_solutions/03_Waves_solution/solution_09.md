# Problem 9: Damped Oscillator

## Given Equation
m d²x/dt² + b dx/dt + kx = 0

---

## 1. General Solution

Solve the characteristic equation:
m r² + b r + k = 0

r = (-b ± √(b² - 4mk)) / (2m)

---

## 2. Classification of Motion

### Underdamped (b² < 4mk)
x(t) = A e^(-γt) cos(ω't + φ)

Where:
γ = b / (2m)  
ω' = √(k/m - γ²)

---

### Critically Damped (b² = 4mk)
x(t) = (A + Bt) e^(-b t / 2m)

---

### Overdamped (b² > 4mk)
x(t) = C e^(r₁t) + D e^(r₂t)

Where:
r₁, r₂ = (-b ± √(b² - 4mk)) / (2m)

---

## 3. Numerical Solution (RK4 Idea)

Convert to system:
dx/dt = v  
dv/dt = (-b v - k x)/m  

Use numerical method (e.g., RK4) to simulate motion over time.

---

## 4. Effect of Damping Parameter b

- Small b → oscillations (underdamped)  
- Critical b → fastest return without oscillation  
- Large b → slow return (overdamped)  

---

## 5. Output Graphs

- x(t): displacement vs time  
- Phase portrait: velocity vs displacement  

---

## 6. HTML Simulation

See file: DampedOscillator.html  

Features:
- Slider to change damping coefficient b  
- Real-time graph of x(t)  
- Visual comparison of damping cases  

---

## Key Idea

The damping parameter b controls how quickly the system loses energy:
- Low damping → oscillations  
- High damping → no oscillation
