
---

# ✅ **Problem 10: Wave Sources Animation**

### Goal:

Create an **HTML animation** where clicking adds point sources of waves:

[
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_0}|^\alpha} \sin(k |\vec{r} - \vec{r_0}| - \omega t)
]

* (\vec{r_0}) = source position
* (\alpha \in [0,2]) adjustable
* Superposition of all sources is shown

---

## 🔹 HTML + JS Code:

```html id="wz4y9m"
<!DOCTYPE html>
<html>
<body>
<canvas id="canvas" width="500" height="500"></canvas>

<script>
let canvas = document.getElementById("canvas");
let ctx = canvas.getContext("2d");

let sources = [];
let A = 50;
let k = 0.1;
let omega = 0.2;
let alpha = 1; // can be changed dynamically

// Add source on click
canvas.onclick = (e) => {
    sources.push({x: e.offsetX, y: e.offsetY});
};

// Draw wave field
function draw(t){
    for(let x=0; x<500; x+=5){
        for(let y=0; y<500; y+=5){
            let u = 0;
            sources.forEach(s => {
                let r = Math.hypot(x-s.x, y-s.y);
                if(r!==0) u += A * Math.sin(k*r - omega*t) / Math.pow(r, alpha);
            });
            let c = 128 + Math.max(Math.min(u,127),-127);
            ctx.fillStyle = `rgb(${c},${c},255)`;
            ctx.fillRect(x,y,5,5);
        }
    }
}

// Animate
function animate(t){
    draw(t/10);
    requestAnimationFrame(animate);
}

animate(0);
</script>
</body>
</html>
```

---

## ✅ **Key Features:**

* Click canvas to **add wave sources**
* Parameter (\alpha) can be adjusted to see amplitude decay with distance
* Visualizes **superposition of waves in real time**

---

