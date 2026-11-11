<div align="center">

<svg width="100%" height="120" viewBox="0 0 900 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed">
        <animate attributeName="stop-color" values="#7c3aed;#06b6d4;#f59e0b;#ec4899;#7c3aed" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#06b6d4">
        <animate attributeName="stop-color" values="#06b6d4;#f59e0b;#ec4899;#7c3aed;#06b6d4" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#ec4899">
        <animate attributeName="stop-color" values="#ec4899;#7c3aed;#06b6d4;#f59e0b;#ec4899" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="900" height="120" fill="#0f172a"/>
  <text x="450" y="55" font-family="monospace" font-size="42" font-weight="bold" fill="url(#g1)" text-anchor="middle" filter="url(#glow)">
    QUANTUM TEA LEAVES
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="95" font-family="monospace" font-size="16" fill="#94a3b8" text-anchor="middle">
    where leaves collapse into flavor states
    <animate attributeName="y" values="95;90;95" dur="4s" repeatCount="indefinite"/>
  </text>
</svg>

<br/>

<svg width="100%" height="40" viewBox="0 0 800 40" xmlns="http://www.w3.org/2000/svg">
  <text x="0" y="28" font-family="monospace" font-size="14" fill="#22d3ee">
    <tspan>&#9670; &#9671; &#9672; &#9673; &#9674; &#9675; &#9676; &#9677; &#9678; &#9679; &#9680; &#9681; &#9682; &#9683; &#9684; &#9685; &#9686; &#9687;</tspan>
    <animateTransform attributeName="transform" type="translate" from="0 0" to="-200 0" dur="12s" repeatCount="indefinite"/>
  </text>
  <text x="400" y="28" font-family="monospace" font-size="14" fill="#a78bfa">
    <tspan>&#9688; &#9689; &#9690; &#9691; &#9692; &#9693; &#9694; &#9695; &#9696; &#9697; &#9698; &#9699; &#9700; &#9701; &#9702; &#9703;</tspan>
    <animateTransform attributeName="transform" type="translate" from="0 0" to="200 0" dur="15s" repeatCount="indefinite"/>
  </text>
</svg>

</div>

---

<svg width="100%" height="80" viewBox="0 0 700 80" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="10" width="680" height="60" rx="12" fill="#1e1b4b" stroke="#6366f1" stroke-width="2">
    <animate attributeName="stroke" values="#6366f1;#a855f7;#ec4899;#6366f1" dur="5s" repeatCount="indefinite"/>
  </rect>
  <text x="350" y="48" font-family="monospace" font-size="18" fill="#e0e7ff" text-anchor="middle">
    Observation collapses the brew into reality
    <animate attributeName="fill" values="#e0e7ff;#c4b5fd;#f0abfc;#e0e7ff" dur="4s" repeatCount="indefinite"/>
  </text>
</svg>

### The Premise

This repository documents nothing useful.  
It exists only as a container for animated SVG experiments that pretend to describe a fictional beverage system in which tea leaves exist in superposition until measured by a teapot.

```
|psi> = alpha |oolong> + beta |matcha> + gamma |assam>
```

When the lid is opened, the wavefunction collapses and a flavor is selected.  
No actual physics is harmed in the making of this README.

---

<div align="center">

<svg width="320" height="220" viewBox="0 0 320 220" xmlns="http://www.w3.org/2000/svg">
  <!-- cup -->
  <path d="M60 80 Q60 180 160 180 Q260 180 260 80 Z" fill="#0f172a" stroke="#38bdf8" stroke-width="3">
    <animate attributeName="stroke" values="#38bdf8;#818cf8;#f472b6;#38bdf8" dur="6s" repeatCount="indefinite"/>
  </path>
  <!-- handle -->
  <path d="M260 100 Q300 100 300 140 Q300 160 260 160" fill="none" stroke="#38bdf8" stroke-width="3">
    <animate attributeName="stroke" values="#38bdf8;#818cf8;#f472b6;#38bdf8" dur="6s" repeatCount="indefinite"/>
  </path>
  <!-- liquid -->
  <ellipse cx="160" cy="95" rx="90" ry="18" fill="#0ea5e9" opacity="0.7">
    <animate attributeName="ry" values="18;22;18" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#0ea5e9;#22d3ee;#67e8f9;#0ea5e9" dur="5s" repeatCount="indefinite"/>
  </ellipse>
  <!-- steam -->
  <path d="M120 70 Q130 40 140 70" fill="none" stroke="#94a3b8" stroke-width="2" opacity="0.6">
    <animate attributeName="d" values="M120 70 Q130 40 140 70;M120 70 Q125 30 140 70;M120 70 Q135 45 140 70;M120 70 Q130 40 140 70" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
  </path>
  <path d="M150 65 Q160 30 170 65" fill="none" stroke="#94a3b8" stroke-width="2" opacity="0.5">
    <animate attributeName="d" values="M150 65 Q160 30 170 65;M150 65 Q155 25 170 65;M150 65 Q165 40 170 65;M150 65 Q160 30 170 65" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="3.5s" repeatCount="indefinite"/>
  </path>
  <path d="M185 70 Q195 35 205 70" fill="none" stroke="#94a3b8" stroke-width="2" opacity="0.55">
    <animate attributeName="d" values="M185 70 Q195 35 205 70;M185 70 Q190 28 205 70;M185 70 Q200 42 205 70;M185 70 Q195 35 205 70" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.25;0.75;0.25" dur="2.8s" repeatCount="indefinite"/>
  </path>
  <!-- floating leaves -->
  <ellipse cx="110" cy="130" rx="12" ry="6" fill="#16a34a" transform="rotate(-30 110 130)">
    <animateTransform attributeName="transform" type="rotate" values="-30 110 130;-20 110 130;-40 110 130;-30 110 130" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="130;125;135;130" dur="3s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="180" cy="145" rx="10" ry="5" fill="#15803d" transform="rotate(25 180 145)">
    <animateTransform attributeName="transform" type="rotate" values="25 180 145;15 180 145;35 180 145;25 180 145" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="145;150;140;145" dur="2.7s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="145" cy="155" rx="9" ry="4.5" fill="#166534" transform="rotate(-10 145 155)">
    <animateTransform attributeName="transform" type="="rotate" values="-10 145 155;0 145 155;-20 145 155;-10 145 155" dur="4.2s" repeatCount="indefinite"/>
  </ellipse>
</svg>

</div>

---

### Flavor Eigenstates

| State | Probability Amplitude | Observed Taste |
|-------|-----------------------|----------------|
| \|oolong\> | 0.58 | floral, roasted |
| \|matcha\> | 0.41 | umami, grassy |
| \|assam\> | 0.33 | malty, strong |
| \|void\> | 0.12 | nothing, briefly |

<svg width="100%" height="30" viewBox="0 0 600 30" xmlns="http://www.w3.org/2000/svg">
  <text x="0" y="22" font-family="monospace" font-size="13" fill="#34d399">
    &#9654; measuring... &#9654; measuring... &#9654; measuring... &#9654; measuring...
    <animateTransform attributeName="transform" type="translate" from="0 0" to="-280 0" dur="8s" repeatCount="indefinite"/>
  </text>
</svg>

---

### Installation of Nothing

```bash
# this repository contains no code that runs
git clone https://github.com/devlopergit04/quantum-tea-leaves.git
cd quantum-tea-leaves
# stare at the README until the leaves decide
```

---

<div align="center">

<svg width="100%" height="100" viewBox="0 0 700 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bar" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="50%" stop-color="#06b6d4"/>
      <stop offset="100%" stop-color="#f43f5e"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="-1 0" to="1 0" dur="4s" repeatCount="indefinite"/>
    </linearGradient>
  </defs>
  <rect x="20" y="30" width="660" height="40" rx="20" fill="#1e293b"/>
  <rect x="20" y="30" width="0" height="40" rx="20" fill="url(#bar)">
    <animate attributeName="width" values="0;660;0" dur="6s" repeatCount="indefinite"/>
  </rect>
  <text x="350" y="55" font-family="monospace" font-size="14" fill="#f1f5f9" text-anchor="middle">
    decoherence progress
  </text>
</svg>

<svg width="100%" height="50" viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg">
  <text x="350" y="30" font-family="monospace" font-size="12" fill="#64748b" text-anchor="middle">
    <tspan fill="#a78bfa">&#9679;</tspan> &#9675; &#9679; &#9675; &#9679; &#9675; &#9679; &#9675; &#9679; &#9675; &#9679; &#9675; &#9679; &#9675; &#9679;
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>

</div>

---

### Contributing

Pull requests that add more animated SVG elements are welcome.  
Pull requests that add actual useful code will be observed until they decohere into nothing.

---

<div align="center">

<svg width="100%" height="60" viewBox="0 0 600 60" xmlns="http://www.w3.org/2000/svg">
  <text x="300" y="25" font-family="monospace" font-size="11" fill="#475569" text-anchor="middle">
    this readme is a measurement apparatus
  </text>
  <text x="300" y="45" font-family="monospace" font-size="11" fill="#334155" text-anchor="middle">
    the leaves know you are watching
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="5s" repeatCount="indefinite"/>
  </text>
</svg>

<svg width="200" height="40" viewBox="0 0 200 40" xmlns="http://www.w3.org/2000/svg">
  <rect width="200" height="40" rx="8" fill="#0f172a" stroke="#4c1d95" stroke-width="1">
    <animate attributeName="stroke" values="#4c1d95;#7c3aed;#4c1d95" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="100" y="25" font-family="monospace" font-size="12" fill="#c4b5fd" text-anchor="middle">
    &#9642; &#9643; &#9644; &#9645; &#9646; &#9647; &#9648;
  </text>
</svg>

</div>
