<div align="center">

<!-- ══════════ ANIMATED SVG HEADER ══════════ -->
<svg width="860" height="280" viewBox="0 0 860 280"
     xmlns="http://www.w3.org/2000/svg" role="img"
     aria-label="Space themed profile header">
  <defs>
    <radialGradient id="bg" cx="50%" cy="50%" r="70%">
      <stop offset="0%"   stop-color="#0d1530"/>
      <stop offset="100%" stop-color="#060b1a"/>
    </radialGradient>

    <!-- Planet gradients -->
    <radialGradient id="pg1" cx="35%" cy="35%">
      <stop offset="0%"   stop-color="#c9a0ff"/>
      <stop offset="55%"  stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#3b1580"/>
    </radialGradient>
    <radialGradient id="pg2" cx="38%" cy="36%">
      <stop offset="0%"   stop-color="#ffb3e6"/>
      <stop offset="55%"  stop-color="#e060a0"/>
      <stop offset="100%" stop-color="#7c1460"/>
    </radialGradient>
    <radialGradient id="pg3" cx="35%" cy="30%">
      <stop offset="0%"   stop-color="#80ffe8"/>
      <stop offset="55%"  stop-color="#00bfa5"/>
      <stop offset="100%" stop-color="#00655a"/>
    </radialGradient>
    <radialGradient id="pg4" cx="35%" cy="30%">
      <stop offset="0%"   stop-color="#ffd580"/>
      <stop offset="55%"  stop-color="#ff8c42"/>
      <stop offset="100%" stop-color="#a84000"/>
    </radialGradient>

    <!-- Nebula -->
    <filter id="blur1"><feGaussianBlur stdDeviation="40"/></filter>
    <filter id="blur2"><feGaussianBlur stdDeviation="28"/></filter>

    <!-- Text gradient -->
    <linearGradient id="tg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#e0c4ff"/>
      <stop offset="35%"  stop-color="#b49dff"/>
      <stop offset="70%"  stop-color="#80d9ff"/>
      <stop offset="100%" stop-color="#ff99d6"/>
    </linearGradient>

    <!-- Clipping -->
    <clipPath id="card"><rect width="860" height="280" rx="22"/></clipPath>

    <!-- Star animations -->
    <animate id="ta"/>
  </defs>

  <g clip-path="url(#card)">
    <!-- Background -->
    <rect width="860" height="280" rx="22" fill="url(#bg)"/>

    <!-- Border -->
    <rect width="860" height="280" rx="22" fill="none"
          stroke="rgba(130,100,255,0.2)" stroke-width="1.5"/>

    <!-- Nebula blobs -->
    <ellipse cx="780" cy="60"  rx="160" ry="120"
             fill="rgba(100,60,220,0.22)"  filter="url(#blur1)"/>
    <ellipse cx="60"  cy="220" rx="130" ry="100"
             fill="rgba(30,160,200,0.14)"  filter="url(#blur1)"/>
    <ellipse cx="720" cy="230" rx="90"  ry="90"
             fill="rgba(220,80,160,0.12)" filter="url(#blur2)"/>

    <!-- ── Stars ── -->
    <!-- Row 1 -->
    <circle cx="20"  cy="18"  r="1.2" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="3.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="8"   r="0.8" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.5;0" dur="2.8s" begin="1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="210" cy="24"  r="1.0" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.8;0" dur="4.1s" begin="0.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="330" cy="12"  r="1.5" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="2.5s" begin="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="440" cy="30"  r="0.9" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.9;0" dur="3.7s" begin="1.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="560" cy="10"  r="1.1" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="3.0s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
    <!-- Row 2 -->
    <circle cx="50"  cy="70"  r="0.9" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="2.2s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="290" cy="60"  r="1.3" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.8;0" dur="3.5s" begin="1.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="55"  r="0.7" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.5;0" dur="4.3s" begin="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="400" cy="90"  r="1.0" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="3.1s" begin="0.6s" repeatCount="indefinite"/>
    </circle>
    <!-- More scattered -->
    <circle cx="160" cy="140" r="0.8" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="2.9s" begin="1.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="250" cy="180" r="1.2" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.8;0" dur="3.8s" begin="0.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="380" cy="200" r="0.7" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.5;0" dur="2.4s" begin="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="480" cy="160" r="1.1" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.9;0" dur="4.0s" begin="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="610" cy="140" r="0.9" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="3.3s" begin="0.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="30"  cy="240" r="1.0" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="2.7s" begin="1.9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="140" cy="260" r="0.8" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.8;0" dur="3.6s" begin="0.2s" repeatCount="indefinite"/>
    </circle>

    <!-- ── Shooting star ── -->
    <line x1="-100" y1="50" x2="0" y2="42"
          stroke="white" stroke-width="1.5" stroke-linecap="round" opacity="0">
      <animateTransform attributeName="transform" type="translate"
        values="0 0; 1000 30" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.05;0.15;0.35;0.45"
        dur="7s" repeatCount="indefinite"/>
    </line>
    <line x1="-60" y1="90" x2="0" y2="85"
          stroke="white" stroke-width="1" stroke-linecap="round" opacity="0">
      <animateTransform attributeName="transform" type="translate"
        values="0 0; 900 20" dur="7s" begin="3.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0;0.8;0.8;0" keyTimes="0;0.05;0.15;0.35;0.45"
        dur="7s" begin="3.5s" repeatCount="indefinite"/>
    </line>

    <!-- ── Planet 1: Big Purple (top right) ── -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0 0; 0 -12; 0 0" dur="7s" repeatCount="indefinite"
        additive="sum" calcMode="spline" keySplines="0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="780" cy="66" r="44" fill="url(#pg1)">
        <animate attributeName="cy" values="66;54;66" dur="7s" repeatCount="indefinite"
          calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
      </circle>
      <!-- Ring -->
      <ellipse cx="780" cy="66" rx="68" ry="14"
               fill="none" stroke="rgba(200,160,255,0.35)" stroke-width="7">
        <animate attributeName="cy" values="66;54;66" dur="7s" repeatCount="indefinite"
          calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
      </ellipse>
      <!-- Planet shine -->
      <circle cx="768" cy="54" r="10" fill="rgba(255,255,255,0.12)">
        <animate attributeName="cy" values="54;42;54" dur="7s" repeatCount="indefinite"
          calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
      </circle>
      <!-- Glow -->
      <circle cx="780" cy="66" r="56" fill="rgba(140,80,255,0.1)" filter="url(#blur2)">
        <animate attributeName="cy" values="66;54;66" dur="7s" repeatCount="indefinite"
          calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
      </circle>
    </g>

    <!-- ── Planet 2: Pink (bottom left) ── -->
    <circle cx="52" cy="210" r="26" fill="url(#pg2)">
      <animate attributeName="cy" values="210;220;210" dur="9s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>
    <circle cx="44" cy="200" r="6" fill="rgba(255,255,255,0.14)">
      <animate attributeName="cy" values="200;210;200" dur="9s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>
    <circle cx="52" cy="210" r="34" fill="rgba(240,100,180,0.1)" filter="url(#blur2)">
      <animate attributeName="cy" values="210;220;210" dur="9s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>

    <!-- ── Planet 3: Teal moon (mid left) ── -->
    <circle cx="68" cy="120" r="18" fill="url(#pg3)">
      <animate attributeName="cy" values="120;130;120" dur="11s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>
    <circle cx="62" cy="113" r="4" fill="rgba(255,255,255,0.15)">
      <animate attributeName="cy" values="113;123;113" dur="11s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>

    <!-- ── Planet 4: Orange mini (bottom right) ── -->
    <circle cx="740" cy="238" r="13" fill="url(#pg4)">
      <animate attributeName="cy" values="238;228;238" dur="8s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>
    <circle cx="735" cy="232" r="3" fill="rgba(255,255,255,0.18)">
      <animate attributeName="cy" values="232;222;232" dur="8s" repeatCount="indefinite"
        calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1"/>
    </circle>

    <!-- ── Planet 5: Tiny blue ── -->
    <circle cx="630" cy="245" r="8" fill="#3b82f6">
      <animate attributeName="cy" values="245;252;245" dur="13s" repeatCount="indefinite"/>
    </circle>
    <circle cx="627" cy="241" r="2" fill="rgba(255,255,255,0.2)">
      <animate attributeName="cy" values="241;248;241" dur="13s" repeatCount="indefinite"/>
    </circle>

    <!-- Sparkle dots -->
    <circle cx="160" cy="52" r="2.5" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2.8s" begin="0.3s" repeatCount="indefinite"/>
      <animate attributeName="r" values="0;2.5;0" dur="2.8s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="430" cy="240" r="2" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="3.2s" begin="1.6s" repeatCount="indefinite"/>
      <animate attributeName="r" values="0;2;0" dur="3.2s" begin="1.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="580" cy="80" r="2" fill="#d8b4fe" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
    </circle>

    <!-- ══════════ TEXT ══════════ -->

    <!-- greeting -->
    <text x="168" y="55"
          font-family="'Segoe UI', system-ui, sans-serif"
          font-size="11" font-weight="700"
          letter-spacing="3"
          fill="rgba(180,160,255,0.7)"
          text-anchor="start">✦  HELLO, UNIVERSE  ✦</text>

    <!-- name / headline -->
    <text x="168" y="105"
          font-family="'Segoe UI', system-ui, sans-serif"
          font-size="44" font-weight="900"
          fill="url(#tg)"
          text-anchor="start">Priyanshi ˙˖⁺✩</text>

    <!-- subtitle -->
    <text x="170" y="132"
          font-family="'Segoe UI', system-ui, sans-serif"
          font-size="14" font-weight="600"
          fill="rgba(180,200,255,0.6)"
          text-anchor="start">full-stack dev  ·  space dreamer  ·  pixel witch</text>

    <!-- divider line -->
    <line x1="168" y1="148" x2="600" y2="148"
          stroke="rgba(150,120,255,0.2)" stroke-width="1"/>

    <!-- status badges (hand-drawn rects) -->
    <rect x="168" y="160" width="100" height="22" rx="11"
          fill="rgba(109,40,217,0.25)" stroke="rgba(167,139,250,0.4)" stroke-width="1"/>
    <text x="218" y="175" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700"
          fill="#c4b5fd" text-anchor="middle">✦ sleepy coder</text>

    <rect x="276" y="160" width="78" height="22" rx="11"
          fill="rgba(190,24,93,0.2)" stroke="rgba(244,114,182,0.4)" stroke-width="1"/>
    <text x="315" y="175" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700"
          fill="#fbcfe8" text-anchor="middle">🌸 she/her</text>

    <rect x="362" y="160" width="140" height="22" rx="11"
          fill="rgba(13,148,136,0.2)" stroke="rgba(45,212,191,0.4)" stroke-width="1"/>
    <text x="432" y="175" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700"
          fill="#99f6e4" text-anchor="middle">🛸 building cool things</text>

    <!-- Tech tags -->
    <text x="168" y="220"
          font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700"
          fill="rgba(180,160,255,0.5)" letter-spacing="2">STACK</text>

    <text x="168" y="244"
          font-family="'Courier New',monospace" font-size="13" font-weight="700"
          fill="rgba(210,190,255,0.8)">Java(Kafka)· React · Node · Postgres · AI</text>

    <!-- Footer -->
    <text x="168" y="268"
          font-family="'Segoe UI',sans-serif" font-size="10"
          fill="rgba(160,150,210,0.4)" letter-spacing="1">✦ made with stardust &amp; caffeine</text>

  </g>
</svg>

---

### `whoami` 🛸

> somewhere between **building web apps** and staring at the stars 🌠
> I write code that's clean, creative & occasionally chaotic.
> Currently orbiting the world of **AI** at warp speed ✨

<br>

### ⚡ Tech Stack

![Java](https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk&logoColor=F5C2E7)
![React](https://img.shields.io/badge/React-0a1628?style=for-the-badge&logo=react&logoColor=80d9ff)
![Node.js](https://img.shields.io/badge/Node.js-0a1a12?style=for-the-badge&logo=node.js&logoColor=99f6e4)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a1428?style=for-the-badge&logo=postgresql&logoColor=80b4ff)
![Vite](https://img.shields.io/badge/Vite-1a0a28?style=for-the-badge&logo=vite&logoColor=fde68a)

<br>

### 🌠 Current Mission

- 🔭 Building a web browser that knows what i like
- 📖 Learning Rust *(it's hard but she's pretty ✨)* and revising loml Java
- 🌐 Contributing to open-source accessibility tools
- ☕ Keeping the matcha industry alive

<br>

### 📡 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Priyanshi-2006&show_icons=true&theme=tokyonight&bg_color=090f22&border_color=7c3aed&icon_color=c084fc&title_color=e0c4ff&text_color=bfb8ff&hide_border=false" height="150"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Priyanshi-2006&layout=compact&theme=tokyonight&bg_color=090f22&border_color=7c3aed&title_color=e0c4ff&text_color=bfb8ff" height="150"/>
</p>

<br>

### 🌸 Find Me

[![LinkedIn](https://img.shields.io/badge/linkedin-0a1228?style=for-the-badge&logo=linkedin&logoColor=93c5fd)](www.linkedin.com/in/priyanshi-juyal-033ba5321)

[![LeetCode](https://img.shields.io/badge/LeetCode-0D1117?style=for-the-badge&logo=leetcode&logoColor=F5C2E7)](https://leetcode.com/u/Priyanshi081/)

<br>

<div align="center">
  <sub>✦ made with stardust & caffeine · updated [[MAY 2026]] ✦</sub>
</div>

</div>
