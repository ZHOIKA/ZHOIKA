<!-- 
 ╔══════════════════════════════════════════════════════════════════╗
 ║                   ZHOIKA — ANGELCORE DARK                      ║
 ║           Preto & Branco · Etéreo · Divino · Sombrio           ║
 ╚══════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ===== ANIMATED ANGEL WINGS SVG ===== -->
<svg width="320" height="120" viewBox="0 0 320 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes wingUp { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-6px)} }
      @keyframes wingDown { 0%,100%{transform:translateY(0)} 50%{transform:translateY(6px)} }
      @keyframes glow { 0%,100%{opacity:0.4} 50%{opacity:1} }
      @keyframes float { 0%,100%{transform:translateY(0) rotate(0deg)} 50%{transform:translateY(-10px) rotate(2deg)} }
      .wing-l { animation: wingUp 2.5s ease-in-out infinite; transform-origin: 160px 60px; }
      .wing-r { animation: wingDown 2.5s ease-in-out infinite; transform-origin: 160px 60px; }
      .glow-ring { animation: glow 3s ease-in-out infinite; }
      .halo-float { animation: float 4s ease-in-out infinite; }
    </style>
  </defs>
  <!-- Left Wing -->
  <g class="wing-l">
    <path d="M160 60 Q120 10 70 20 Q40 25 20 50 Q10 65 5 80 Q15 70 35 65 Q60 58 80 55 L160 60Z" 
          fill="white" opacity="0.15"/>
    <path d="M160 60 Q130 15 85 22 Q55 28 35 50 Q25 62 20 75 Q30 68 50 62 Q75 54 95 50 L160 60Z" 
          fill="white" opacity="0.25"/>
    <path d="M160 60 Q140 25 100 28 Q75 32 55 50 Q45 60 40 70 Q50 64 65 58 Q85 50 105 48 L160 60Z" 
          fill="white" opacity="0.35"/>
  </g>
  <!-- Right Wing -->
  <g class="wing-r">
    <path d="M160 60 Q200 10 250 20 Q280 25 300 50 Q310 65 315 80 Q305 70 285 65 Q260 58 240 55 L160 60Z" 
          fill="white" opacity="0.15"/>
    <path d="M160 60 Q190 15 235 22 Q265 28 285 50 Q295 62 300 75 Q290 68 270 62 Q245 54 225 50 L160 60Z" 
          fill="white" opacity="0.25"/>
    <path d="M160 60 Q180 25 220 28 Q245 32 265 50 Q275 60 280 70 Q270 64 255 58 Q235 50 215 48 L160 60Z" 
          fill="white" opacity="0.35"/>
  </g>
  <!-- Glowing Halo -->
  <g class="halo-float">
    <ellipse cx="160" cy="30" rx="28" ry="8" fill="none" stroke="white" stroke-width="2.5" opacity="0.7" class="glow-ring"/>
    <ellipse cx="160" cy="30" rx="32" ry="10" fill="none" stroke="white" stroke-width="1" opacity="0.3"/>
    <ellipse cx="160" cy="30" rx="22" ry="6" fill="white" opacity="0.08"/>
  </g>
  <!-- Stars -->
  <text x="70" y="18" fill="white" opacity="0.5" font-size="10">✦</text>
  <text x="245" y="15" fill="white" opacity="0.4" font-size="8">✦</text>
  <text x="130" y="12" fill="white" opacity="0.6" font-size="6">✦</text>
  <text x="195" y="16" fill="white" opacity="0.3" font-size="7">✦</text>
</svg>

<!-- ===== GLOWING NAME ===== -->
<h1 style="font-family: 'Georgia', serif; font-size: 52px; margin: 0; letter-spacing: 8px; color: #fff; text-shadow: 0 0 20px rgba(255,255,255,0.3), 0 0 60px rgba(255,255,255,0.1);">
  Z H O I K A
</h1>

<!-- ===== ANIMATED SUBTITLE ===== -->
<p style="font-family: 'Courier New', monospace; font-size: 14px; color: #aaa; letter-spacing: 6px; text-transform: uppercase; margin-top: -8px; border-right: 2px solid #fff; display: inline-block; white-space: nowrap; overflow: hidden; animation: typing 3.5s steps(30) 1s forwards, blink 0.8s step-end infinite;">
  ❝ fall from grace, rise in code ❞
</p>

<style>
  @keyframes typing { from { width: 0 } to { width: 320px } }
  @keyframes blink { 50% { border-color: transparent } }
</style>

<br><br>

<!-- ===== ANGELIC DIVIDER ===== -->
<svg width="400" height="30" viewBox="0 0 400 30" xmlns="http://www.w3.org/2000/svg">
  <line x1="50" y1="15" x2="150" y2="15" stroke="white" stroke-width="0.5" opacity="0.3"/>
  <text x="200" y="20" fill="white" opacity="0.6" font-size="14" text-anchor="middle">✧</text>
  <text x="185" y="20" fill="white" opacity="0.3" font-size="8" text-anchor="middle">✧</text>
  <text x="215" y="20" fill="white" opacity="0.3" font-size="8" text-anchor="middle">✧</text>
  <line x1="250" y1="15" x2="350" y2="15" stroke="white" stroke-width="0.5" opacity="0.3"/>
</svg>

</div>

<br>

<!-- ===== SCROLLING QUOTES MARQUEE ===== -->
<marquee behavior="scroll" direction="left" scrollamount="4" style="color: #666; font-family: 'Georgia', serif; font-style: italic; font-size: 13px; letter-spacing: 2px;">
  ✦ in the garden of code, every error is a prayer ✦  ·  ✦  the darker the night, the brighter the stars ✦  ·  ✦  code is my liturgy, the terminal is my cathedral ✦  ·  ✦  et lux in tenebris lucet ✦  ·  ✦  broken wings still dream of flight ✦
</marquee>

<marquee behavior="scroll" direction="right" scrollamount="3" style="color: #444; font-family: 'Georgia', serif; font-style: italic; font-size: 11px; letter-spacing: 1px; margin-top: 2px;">
  ✦  faith · code · darkness · light  ✦  ·  ✦  angelus ex machina  ✦  ·  ✦  from ashes, we compile ✦
</marquee>

<br>

<!-- ===== FLOATING PARTICLES / FEATHERS (CSS only) ===== -->
<style>
  @keyframes featherFall {
    0%   { transform: translateY(-20px) rotate(0deg); opacity: 0; }
    10%  { opacity: 0.6; }
    90%  { opacity: 0.4; }
    100% { transform: translateY(600px) rotate(360deg); opacity: 0; }
  }
  @keyframes featherFall2 {
    0%   { transform: translateY(-30px) rotate(180deg); opacity: 0; }
    15%  { opacity: 0.5; }
    85%  { opacity: 0.3; }
    100% { transform: translateY(580px) rotate(540deg); opacity: 0; }
  }
  @keyframes twinkle {
    0%,100% { opacity: 0.1; transform: scale(0.8); }
    50%     { opacity: 0.8; transform: scale(1.2); }
  }
  .feather { position: fixed; pointer-events: none; z-index: 999; font-size: 14px; }
  .feather:nth-child(1)  { left: 5%;  animation: featherFall  8s linear infinite; animation-delay: 0s; }
  .feather:nth-child(2)  { left: 15%; animation: featherFall2 10s linear infinite; animation-delay: 2s; }
  .feather:nth-child(3)  { left: 25%; animation: featherFall  7s linear infinite; animation-delay: 4s; }
  .feather:nth-child(4)  { left: 35%; animation: featherFall2 9s linear infinite; animation-delay: 1s; }
  .feather:nth-child(5)  { left: 45%; animation: featherFall  11s linear infinite; animation-delay: 3s; }
  .feather:nth-child(6)  { left: 55%; animation: featherFall2 8s linear infinite; animation-delay: 5s; }
  .feather:nth-child(7)  { left: 65%; animation: featherFall  10s linear infinite; animation-delay: 0.5s; }
  .feather:nth-child(8)  { left: 75%; animation: featherFall2 7s linear infinite; animation-delay: 3.5s; }
  .feather:nth-child(9)  { left: 85%; animation: featherFall  9s linear infinite; animation-delay: 2.5s; }
  .feather:nth-child(10) { left: 95%; animation: featherFall2 11s linear infinite; animation-delay: 1.5s; }
</style>

<div class="feather" style="color: rgba(255,255,255,0.12);">🪶</div>
<div class="feather" style="color: rgba(255,255,255,0.10);">🕊️</div>
<div class="feather" style="color: rgba(255,255,255,0.08);">🪶</div>
<div class="feather" style="color: rgba(255,255,255,0.12);">🕊️</div>
<div class="feather" style="color: rgba(255,255,255,0.06);">🪶</div>
<div class="feather" style="color: rgba(255,255,255,0.10);">🕊️</div>
<div class="feather" style="color: rgba(255,255,255,0.08);">🪶</div>
<div class="feather" style="color: rgba(255,255,255,0.12);">🕊️</div>
<div class="feather" style="color: rgba(255,255,255,0.06);">🪶</div>
<div class="feather" style="color: rgba(255,255,255,0.10);">🕊️</div>

<!-- ===== BACKGROUND OVERLAY ===== -->
<div style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; z-index: -1; background: radial-gradient(ellipse at center, rgba(255,255,255,0.015) 0%, transparent 70%);"></div>

---

<!-- ===== ABOUT ME SECTION ===== -->
<div align="center" style="animation: fadeInUp 1s ease-out;">

### ❛ angelus ex machina ❜

<br>

<table style="border: none; background: transparent;">
  <tr>
    <td width="180" valign="top" style="border: none; padding: 10px;">

<!-- Animated Profile SVG -->
<svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes breathe { 0%,100%{r:35;opacity:0.8} 50%{r:38;opacity:1} }
      @keyframes spin { 100%{transform:rotate(360deg)} }
      @keyframes dotPulse { 0%,100%{opacity:0.3} 50%{opacity:1} }
      .breathe { animation: breathe 4s ease-in-out infinite; }
      .halo-spin { animation: spin 12s linear infinite; transform-origin: 75px 45px; }
    </style>
  </defs>
  <!-- Halo -->
  <ellipse class="halo-spin" cx="75" cy="45" rx="45" ry="14" fill="none" stroke="white" stroke-width="1" opacity="0.25"/>
  <ellipse class="halo-spin" cx="75" cy="45" rx="40" ry="11" fill="none" stroke="white" stroke-width="0.5" opacity="0.12"/>
  <!-- Body/Figure - angel silhouette -->
  <circle cx="75" cy="65" r="35" fill="white" opacity="0.06" class="breathe"/>
  <circle cx="75" cy="60" r="20" fill="white" opacity="0.08"/>
  <path d="M60 80 Q67 90 75 88 Q83 90 90 80 L85 105 Q80 112 75 112 Q70 112 65 105 Z" fill="white" opacity="0.06"/>
  <!-- Wings small -->
  <path d="M60 70 Q40 55 30 60 Q25 62 28 70 Q35 72 50 70" fill="white" opacity="0.1"/>
  <path d="M90 70 Q110 55 120 60 Q125 62 122 70 Q115 72 100 70" fill="white" opacity="0.1"/>
  <!-- Center light -->
  <circle cx="75" cy="60" r="6" fill="white" opacity="0.15"/>
  <circle cx="75" cy="60" r="3" fill="white" opacity="0.3"/>
  <!-- Pulsing dots -->
  <circle cx="50" cy="90" r="1.5" fill="white" style="animation:dotPulse 2s ease-in-out infinite"/>
  <circle cx="100" cy="90" r="1.5" fill="white" style="animation:dotPulse 2s ease-in-out infinite 1s"/>
</svg>

  </td>
  <td valign="top" style="border: none; padding: 10px; text-align: left;">

<p style="font-family: 'Georgia', serif; color: #ccc; font-size: 15px; line-height: 1.8; letter-spacing: 0.5px;">
  <b style="color: #fff; font-size: 18px;">Davi Gomes</b><br>
  <span style="color: #888;">@ZHOIKA</span>
</p>

<p style="font-family: 'Georgia', serif; color: #999; font-size: 14px; line-height: 1.8; font-style: italic;">
  ♱ criador do <b style="color: #fff; font-style: normal;">Zyro</b> — personalizando o Discord no Android com estilo e alma ♱
</p>

<p style="color: #777; font-size: 13px; line-height: 1.8; font-family: 'Courier New', monospace;">
  <span style="color: #aaa;">⟫</span> Kotlin · Android · CLI · Dark Arts<br>
  <span style="color: #aaa;">⟫</span> code ∞ chaos ∞ creation
</p>

<p style="color: #555; font-size: 12px; font-family: 'Courier New', monospace; margin-top: 10px; letter-spacing: 1px;">
  [ fallen · angel · developer ]
</p>

  </td>
  </tr>
</table>

</div>

<br>

---

<!-- ===== SCROLL ANIMATED PROJECTS ===== -->
<style>
  @keyframes slideInLeft {
    0%   { opacity: 0; transform: translateX(-60px); }
    100% { opacity: 1; transform: translateX(0); }
  }
  @keyframes slideInRight {
    0%   { opacity: 0; transform: translateX(60px); }
    100% { opacity: 1; transform: translateX(0); }
  }
  @keyframes fadeScale {
    0%   { opacity: 0; transform: scale(0.85); }
    100% { opacity: 1; transform: scale(1); }
  }
  @keyframes borderPulse {
    0%,100% { border-color: rgba(255,255,255,0.1); }
    50%     { border-color: rgba(255,255,255,0.3); }
  }
  @keyframes shimmer {
    0%   { background-position: -200% center; }
    100% { background-position: 200% center; }
  }
  .proj-card {
    transition: all 0.4s ease;
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 12px;
    padding: 20px;
    margin: 15px 0;
    background: rgba(255,255,255,0.02);
    backdrop-filter: blur(4px);
  }
  .proj-card:hover {
    border-color: rgba(255,255,255,0.3);
    background: rgba(255,255,255,0.05);
    transform: translateY(-4px);
    box-shadow: 0 8px 32px rgba(0,0,0,0.3), 0 0 20px rgba(255,255,255,0.05);
  }
  .proj-card h3 {
    animation: shimmer 3s linear infinite;
    background: linear-gradient(90deg, #fff, #888, #fff);
    background-size: 200% 100%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
</style>

<div align="center">
  <h2 style="font-family: 'Georgia', serif; color: #fff; font-weight: 300; letter-spacing: 6px; text-transform: uppercase; font-size: 18px;">
    ✧ grimoire ✧
  </h2>
  <p style="font-family: 'Georgia', serif; color: #666; font-style: italic; font-size: 13px; margin-top: -8px;">
    Projects etched in light and shadow
  </p>
</div>

<br>

<!-- PROJECT 1: Zyro -->
<div class="proj-card" style="animation: slideInLeft 0.8s ease-out;">

### ❝ Zyro ❞

**Android · Kotlin · Discord**

> Personalize sua presença no Discord com estilo, controle e uma experiência moderna no Android.

<div align="right">
  <a href="https://github.com/ZHOIKA/Zyro" style="color: #aaa; text-decoration: none; font-family: 'Courier New', monospace; font-size: 13px; letter-spacing: 1px;">
    [ explore the abyss ⟶ ]
  </a>
</div>

</div>

<!-- PROJECT 2: ZYRO-CLI -->
<div class="proj-card" style="animation: slideInRight 0.8s ease-out; animation-delay: 0.2s; animation-fill-mode: both;">

### ❝ ZYRO-CLI ❞

**CLI · Automation · Power**

> The command-line incarnation of Zyro's spirit — dark, fast, and elegant.

<div align="right">
  <a href="https://github.com/ZHOIKA/ZYRO-CLI" style="color: #aaa; text-decoration: none; font-family: 'Courier New', monospace; font-size: 13px; letter-spacing: 1px;">
    [ invoke the terminal ⟶ ]
  </a>
</div>

</div>

<br>

---

<!-- ===== GITHUB STATS WITH ANGEL MOTIF ===== -->
<div align="center" style="animation: fadeScale 1s ease-out;">

<h2 style="font-family: 'Georgia', serif; color: #fff; font-weight: 300; letter-spacing: 6px; text-transform: uppercase; font-size: 18px;">
  ✧ celestial ledger ✧
</h2>

<br>

<!-- Stats Cards -->
<table style="border: none; background: transparent;">
  <tr>
    <td width="400" style="border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; padding: 16px; background: rgba(255,255,255,0.02);">

![ZHOIKA's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ZHOIKA&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&icon_color=ffffff&border_radius=8&count_private=true)

    </td>
    <td width="15" style="border: none;"></td>
    <td width="260" style="border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; padding: 16px; background: rgba(255,255,255,0.02);">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ZHOIKA&layout=compact&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&border_radius=8)

    </td>
  </tr>
</table>

<br>

<!-- Animated Contribution Graph -->
![ZHOIKA's Graph](https://github-readme-activity-graph.vercel.app/graph?username=ZHOIKA&bg_color=0a0a0a&color=ffffff&line=ffffff&point=555555&area=true&area_color=ffffff&hide_border=true&radius=8)

<br>

<svg width="300" height="24" viewBox="0 0 300 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="12" x2="120" y2="12" stroke="white" stroke-width="0.3" opacity="0.2"/>
  <text x="150" y="18" fill="white" opacity="0.3" font-size="12" text-anchor="middle" font-family="Georgia">+</text>
  <line x1="180" y1="12" x2="270" y2="12" stroke="white" stroke-width="0.3" opacity="0.2"/>
</svg>

</div>

<br>

---

<!-- ===== ANGELIC SCROLLING FOOTER ===== -->
<div align="center">

<marquee behavior="scroll" direction="left" scrollamount="2" style="color: #333; font-family: 'Georgia', serif; font-size: 11px; letter-spacing: 3px; text-transform: uppercase;">
  ✧  et lux in tenebris lucet  ✧  ·  ✧  tenebrae factae sunt  ✧  ·  ✧  ex machina  ✧  ·  ✧  de profundis  ✧  ·  ✧  ad astra per aspera  ✧
</marquee>

<br>

<!-- Animated Closing Halo -->
<svg width="120" height="50" viewBox="0 0 120 50" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes haloSpin { 100%{transform:rotate(360deg)} }
      @keyframes haloPulse { 0%,100%{opacity:0.2} 50%{opacity:0.6} }
      .h-final { animation: haloSpin 8s linear infinite; transform-origin: 60px 20px; }
      .h-pulse { animation: haloPulse 2s ease-in-out infinite; }
    </style>
  </defs>
  <ellipse class="h-final" cx="60" cy="20" rx="40" ry="12" fill="none" stroke="white" stroke-width="0.8" opacity="0.3"/>
  <ellipse class="h-final" cx="60" cy="20" rx="34" ry="9" fill="none" stroke="white" stroke-width="0.4" opacity="0.15"/>
  <circle cx="60" cy="20" r="4" fill="white" opacity="0.1" class="h-pulse"/>
  <text x="60" y="44" fill="white" opacity="0.15" font-size="8" text-anchor="middle" font-family="Georgia">✧</text>
</svg>

<p style="font-family: 'Courier New', monospace; font-size: 10px; color: #333; letter-spacing: 4px; margin-top: 8px;">
  ✦  ZHOIKA · MMXXVI  ✦
</p>

<p style="font-family: 'Georgia', serif; font-size: 11px; color: #222; font-style: italic; letter-spacing: 1px;">
  "even fallen angels can write their own heaven"
</p>

<br>

<!-- Visitor Counter -->
<img src="https://komarev.com/ghpvc/?username=ZHOIKA&color=333333&style=flat&label=𝔳𝔦𝔰𝔦𝔱𝔬𝔯𝔰&abbreviated=true" alt="visitors" style="filter: grayscale(1); opacity: 0.4;">

</div>

<br>

<!-- ===== INVISIBLE SCROLL ANCHOR TRIGGERS ===== -->
<!-- These create a subtle parallax/scroll effect via CSS hover on sections -->
<style>
  /* Scroll-reveal style animations */
  @keyframes revealUp {
    0% { opacity: 0; transform: translateY(30px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  .reveal {
    opacity: 0;
    animation: revealUp 0.8s ease-out forwards;
  }
  .reveal:nth-child(1) { animation-delay: 0.1s; }
  .reveal:nth-child(2) { animation-delay: 0.3s; }
  .reveal:nth-child(3) { animation-delay: 0.5s; }
  .reveal:nth-child(4) { animation-delay: 0.7s; }
  .reveal:nth-child(5) { animation-delay: 0.9s; }
</style>

<!-- Make horizontal rules ethereal -->
<style>
  hr {
    border: none;
    height: 0.5px;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.15), transparent);
    margin: 30px 0;
  }
  body {
    background: #0a0a0a;
    color: #ccc;
  }
  /* Links */
  a { color: #bbb; transition: color 0.3s; }
  a:hover { color: #fff; }
  /* Selection */
  ::selection { background: rgba(255,255,255,0.15); color: #fff; }
</style>
