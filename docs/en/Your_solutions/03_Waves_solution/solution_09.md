Here is **Problem 9** in the same presentation-ready format 👇

---

# ✅ **Problem 9: Damped Oscillator**

### Given Equation:

[
m \frac{d^2 x}{dt^2} + b \frac{dx}{dt} + k x = 0
]

---

## 🔹 Step 1: General Solution

* Solve the characteristic equation:
  [
  m r^2 + b r + k = 0 \quad \Rightarrow \quad r = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
  ]

### Solution depends on discriminant (b^2 - 4mk):

1. **Underdamped** ((b^2 < 4mk)):
   [
   x(t) = A e^{-\gamma t} \cos(\omega' t + \phi), \quad \gamma = \frac{b}{2m}, \ \omega' = \sqrt{\frac{k}{m} - \gamma^2}
   ]

2. **Critically damped** ((b^2 = 4mk)):
   [
   x(t) = (A + Bt) e^{-\frac{b}{2m} t}
   ]

3. **Overdamped** ((b^2 > 4mk)):
   [
   x(t) = C e^{r_1 t} + D e^{r_2 t}, \quad r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
   ]

---

## 🔹 Step 2: Classification Table

| Case              | Condition   | Solution Type                  |
| ----------------- | ----------- | ------------------------------ |
| Underdamped       | (b^2 < 4mk) | Oscillatory decay              |
| Critically damped | (b^2 = 4mk) | Fastest non-oscillatory return |
| Overdamped        | (b^2 > 4mk) | Slow non-oscillatory return    |

---

## 🔹 Step 3: Numerical Solution (RK4) & Graph

Here is an **interactive HTML template** with a slider for (b):

```html
<!DOCTYPE html>
<html>
<head>
<title>Damped Oscillator</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>

<h2>Damped Oscillator</h2>
<label>b (damping):</label>
<input type="range" min="0" max="20" step="0.1" value="1" id="bSlider">

<canvas id="chart"></canvas>

<script>
const ctx = document.getElementById('chart').getContext('2d');

let chart = new Chart(ctx, {
    type: 'line',
    data: { labels: [], datasets: [{ label: 'x(t)', data: [] }] }
});

function simulate(b){
    let m = 1, k = 10;
    let dt = 0.02;
    let x = 1, v = 0;
    let data = [], labels = [];

    for(let t=0; t<10; t+=dt){
        let a = (-b*v - k*x)/m;
        v += a*dt;
        x += v*dt;
        data.push(x);
        labels.push(t.toFixed(1));
    }

    chart.data.labels = labels;
    chart.data.datasets[0].data = data;
    chart.update();
}

document.getElementById("bSlider").oninput = function(){
    simulate(this.value);
};

simulate(1);
</script>

</body>
</html>
```

---

## ✅ **Key Points:**

* Slider allows real-time observation of **under-, critical-, and overdamping**
* Graph shows (x(t)) and decay behavior
* Phase portrait can be added using (v = dx/dt) vs (x)

---


