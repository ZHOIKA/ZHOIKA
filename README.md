<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--              ANGELCORE HEADER — SIMPLE & RELIABLE         -->
<!--       SVG SMIL animations that work on GitHub            -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="480" height="210" viewBox="0 0 480 210" xmlns="http://www.w3.org/2000/svg">

  <!-- glow -->
  <ellipse cx="240" cy="110" rx="100" ry="80" fill="white" opacity="0.015">
    <animate attributeName="opacity" values="0.015;0.05;0.015" dur="4s" repeatCount="indefinite"/>
  </ellipse>

  <!-- twinkling stars ✧ -->
  <text x="50" y="30" fill="white" font-size="11" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.8;0.8;0" dur="5s" repeatCount="indefinite" begin="0s"/>
  </text>
  <text x="400" y="25" fill="white" font-size="10" font-family="Georgia" opacity="0">
    ✦
    <animate attributeName="opacity" values="0;0;0.7;0.7;0" dur="6s" repeatCount="indefinite" begin="1.5s"/>
  </text>
  <text x="160" y="18" fill="white" font-size="7" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="4s" repeatCount="indefinite" begin="0.8s"/>
  </text>
  <text x="340" y="15" fill="white" font-size="6" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4.5s" repeatCount="indefinite" begin="2.5s"/>
  </text>
  <text x="440" y="50" fill="white" font-size="8" font-family="Georgia" opacity="0">
    ✦
    <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="5.5s" repeatCount="indefinite" begin="1s"/>
  </text>
  <text x="28" y="55" fill="white" font-size="7" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="3.8s" repeatCount="indefinite" begin="3s"/>
  </text>
  <text x="260" y="22" fill="white" font-size="5" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
  </text>
  <text x="120" y="45" fill="white" font-size="6" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4.2s" repeatCount="indefinite" begin="2s"/>
  </text>

  <!-- shooting stars -->
  <line x1="40" y1="12" x2="70" y2="42" stroke="white" stroke-width="0.6" opacity="0">
    <animate attributeName="opacity" values="0;0.8;0" dur="3s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="x1" values="40;110" dur="3s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="y1" values="12;82" dur="3s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="x2" values="70;140" dur="3s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="y2" values="42;112" dur="3s" repeatCount="indefinite" begin="0s"/>
  </line>
  <line x1="430" y1="18" x2="400" y2="48" stroke="white" stroke-width="0.6" opacity="0">
    <animate attributeName="opacity" values="0;0.7;0" dur="4s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="x1" values="430;350" dur="4s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="y1" values="18;75" dur="4s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="x2" values="400;320" dur="4s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="y2" values="48;105" dur="4s" repeatCount="indefinite" begin="2s"/>
  </line>

  <!-- left wing floating -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-7; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M240 100 Q185 25 100 35 Q55 43 25 78 Q12 105 15 128 Q28 110 60 100 Q95 88 130 82 L240 100Z" fill="white" opacity="0.06"/>
    <path d="M240 100 Q190 35 118 44 Q74 52 45 82 Q34 102 30 122 Q46 108 74 98 Q104 86 140 80 L240 100Z" fill="white" opacity="0.10"/>
    <path d="M240 100 Q195 46 135 52 Q94 60 65 86 Q52 100 48 116 Q66 104 88 95 Q116 84 150 78 L240 100Z" fill="white" opacity="0.15"/>
  </g>

  <!-- right wing floating -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,7; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M240 100 Q295 25 380 35 Q425 43 455 78 Q468 105 465 128 Q452 110 420 100 Q385 88 350 82 L240 100Z" fill="white" opacity="0.06"/>
    <path d="M240 100 Q290 35 362 44 Q406 52 435 82 Q446 102 450 122 Q434 108 406 98 Q376 86 340 80 L240 100Z" fill="white" opacity="0.10"/>
    <path d="M240 100 Q285 46 345 52 Q386 60 415 86 Q428 100 432 116 Q414 104 392 95 Q364 84 330 78 L240 100Z" fill="white" opacity="0.15"/>
  </g>

  <!-- halo -->
  <circle cx="240" cy="100" r="38" fill="none" stroke="white" stroke-width="0.5" opacity="0.25">
    <animate attributeName="r" values="38;52;38" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.25;0.6;0.25" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="240" cy="100" r="16" fill="white" opacity="0.035">
    <animate attributeName="r" values="16;22;16" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.035;0.09;0.035" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <!-- orbit ring -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 240 52" to="360 240 52" dur="16s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="52" rx="50" ry="14" fill="none" stroke="white" stroke-width="0.35" opacity="0.12"/>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="360 240 52" to="0 240 52" dur="20s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="52" rx="60" ry="16" fill="none" stroke="white" stroke-width="0.25" opacity="0.07"/>
  </g>

  <!-- ZHOIKA title -->
  <text x="240" y="172" fill="white" font-size="30" text-anchor="middle" font-family="Georgia, 'Times New Roman', serif" letter-spacing="10" opacity="0.85">
    ZHOIKA
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- subtitle -->
  <text x="240" y="196" fill="white" font-size="9" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="12" opacity="0.3">
    ET LVX IN TENEBRIS LVCET
    <animate attributeName="opacity" values="0.2;0.5;0.2" dur="4s" repeatCount="indefinite"/>
  </text>

</svg>

<br>

<!-- tagline -->
<svg width="460" height="36" viewBox="0 0 460 36" xmlns="http://www.w3.org/2000/svg">
  <text x="230" y="24" fill="white" opacity="0.5" font-size="13" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    fallen angels write their own heaven
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="3s" repeatCount="indefinite"/>
  </text>
</svg>

<br>

<!-- divider -->
<svg width="320" height="28" viewBox="0 0 320 28" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="14" x2="300" y2="14" stroke="white" stroke-width="0.3" opacity="0.12"/>
  <circle cx="160" cy="14" r="3" fill="white" opacity="0.2">
    <animate attributeName="opacity" values="0.15;0.6;0.15" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="3s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--         PAC-MAN — CONFIRMED WORKING                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="30" viewBox="0 0 360 30" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="18" fill="white" opacity="0.3" font-size="11" text-anchor="middle" font-family="Georgia, serif" letter-spacing="8">
    ouroboros
  </text>
  <line x1="70" y1="26" x2="290" y2="26" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br>

<!-- Pac-Man (confirmed working - already on output branch) -->
<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/pacman-contribution-graph-dark.svg" width="100%" style="max-width:880px; filter:grayscale(0.3);" alt="pac-man contributions" />

<br>

<svg width="380" height="18" viewBox="0 0 380 18" xmlns="http://www.w3.org/2000/svg">
  <text x="190" y="12" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    the serpent devours the stars
  </text>
</svg>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--           SNAKE GIF — GERA APÓS O PRÓXIMO PUSH           -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="30" viewBox="0 0 360 30" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="18" fill="white" opacity="0.3" font-size="11" text-anchor="middle" font-family="Georgia, serif" letter-spacing="8">
    legion
  </text>
  <line x1="70" y1="26" x2="290" y2="26" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br>

<!-- Snake GIF (will auto-generate after this push) -->
<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/snake-output/github-contribution-grid-snake.gif" width="100%" style="max-width:800px; filter:grayscale(0.3); border-radius:6px;" alt="snake eating contributions" />

<br>

<svg width="380" height="18" viewBox="0 0 380 18" xmlns="http://www.w3.org/2000/svg">
  <text x="190" y="12" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    the many that move as one
  </text>
</svg>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   GITANIMALS                              -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="30" viewBox="0 0 360 30" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="18" fill="white" opacity="0.3" font-size="11" text-anchor="middle" font-family="Georgia, serif" letter-spacing="8">
    menagerie
  </text>
  <line x1="70" y1="26" x2="290" y2="26" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br>

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/ZHOIKA" width="100%" height="110" style="max-width:800px; filter:grayscale(0.6);" alt="git animals" />
</a>

<br>

<svg width="340" height="18" viewBox="0 0 340 18" xmlns="http://www.w3.org/2000/svg">
  <text x="170" y="12" fill="white" opacity="0.12" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="3" font-style="italic">
    creatures born from the deep of commits
  </text>
</svg>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    GRIMOIRE / PROJECTS                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    grimoire
  </text>
  <line x1="100" y1="34" x2="300" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

</div>

<div style="border:1px solid rgba(255,255,255,0.05); border-radius:12px; padding:24px 30px; margin:18px auto; background:rgba(255,255,255,0.012); max-width:700px; transition:border-color 0.6s ease, background 0.6s ease, transform 0.6s ease, box-shadow 0.6s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.18)'; this.style.background='rgba(255,255,255,0.025)'; this.style.transform='translateY(-4px)'; this.style.boxShadow='0 8px 40px rgba(0,0,0,0.5)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.05)'; this.style.background='rgba(255,255,255,0.012)'; this.style.transform='none'; this.style.boxShadow='none'">

<span style="font-family:Georgia, serif; color:#fff; font-size:16px; letter-spacing:4px; font-style:italic;">Zyro</span>
<br>
<span style="font-family:'Courier New', monospace; font-size:11px; color:#444; letter-spacing:1px;">Android · Kotlin · Discord</span>

<p style="font-family:Georgia, serif; color:#777; font-size:14px; line-height:1.7; font-style:italic; margin-top:8px;">
  Personalize sua presenca no Discord com estilo, controle e uma experiencia moderna no Android.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/Zyro" style="font-family:'Courier New', monospace; font-size:11px; color:#555; text-decoration:none; letter-spacing:2px;">
    explore the abyss ››
  </a>
</div>

</div>

<br>

<div style="border:1px solid rgba(255,255,255,0.05); border-radius:12px; padding:24px 30px; margin:18px auto; background:rgba(255,255,255,0.012); max-width:700px; transition:border-color 0.6s ease, background 0.6s ease, transform 0.6s ease, box-shadow 0.6s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.18)'; this.style.background='rgba(255,255,255,0.025)'; this.style.transform='translateY(-4px)'; this.style.boxShadow='0 8px 40px rgba(0,0,0,0.5)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.05)'; this.style.background='rgba(255,255,255,0.012)'; this.style.transform='none'; this.style.boxShadow='none'">

<span style="font-family:Georgia, serif; color:#fff; font-size:16px; letter-spacing:4px; font-style:italic;">ZYRO-CLI</span>
<br>
<span style="font-family:'Courier New', monospace; font-size:11px; color:#444; letter-spacing:1px;">CLI · Automation · Power</span>

<p style="font-family:Georgia, serif; color:#777; font-size:14px; line-height:1.7; font-style:italic; margin-top:8px;">
  The command-line incarnation of Zyro's spirit — dark, fast, and elegant.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/ZYRO-CLI" style="font-family:'Courier New', monospace; font-size:11px; color:#555; text-decoration:none; letter-spacing:2px;">
    invoke the terminal ››
  </a>
</div>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                 CELESTIAL LEDGER / STATS                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="460" height="40" viewBox="0 0 460 40" xmlns="http://www.w3.org/2000/svg">
  <text x="230" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    celestial ledger
  </text>
  <line x1="110" y1="34" x2="350" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=ZHOIKA&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&icon_color=ffffff&border_radius=8&count_private=true&include_all_commits=true&hide_title=true" alt="github stats" style="max-width:450px;" />

<br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZHOIKA&layout=compact&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&border_radius=8&hide_title=true" alt="top languages" style="max-width:400px;" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ZHOIKA&bg_color=0a0a0a&color=ffffff&line=ffffff&point=555555&area=true&area_color=ffffff&hide_border=true&radius=4&custom_title=Contribution+Graph" alt="contribution graph" style="max-width:100%; filter:grayscale(0.3);" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ZHOIKA&hide_border=true&background=0d0d0d&stroke=ffffff&ring=ffffff&fire=ffffff&currStreakNum=ffffff&sideNums=aaaaaa&currStreakLabel=ffffff&sideLabels=888888&dates=666666" alt="streak" style="max-width:450px;" />

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    RELIQUARY / TROPHIES                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="40" viewBox="0 0 420 40" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    reliquary
  </text>
  <line x1="95" y1="34" x2="325" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=ZHOIKA&theme=flat&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8&title=Stars,Followers,Commits,PullRequest,Issues,Repositories" alt="github trophy" style="max-width:100%; filter:grayscale(0.9);" />

<br>

<svg width="360" height="18" viewBox="0 0 360 18" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="12" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    trophies from the unseen war
  </text>
</svg>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     ARMAMENTS / SKILLS                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    armaments
  </text>
  <line x1="85" y1="34" x2="315" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://img.shields.io/badge/Kotlin-000000?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=111" alt="Kotlin"/>
<img src="https://img.shields.io/badge/Android-000000?style=for-the-badge&logo=android&logoColor=white&labelColor=111" alt="Android"/>
<img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white&labelColor=111" alt="Git"/>
<img src="https://img.shields.io/badge/Discord-000000?style=for-the-badge&logo=discord&logoColor=white&labelColor=111" alt="Discord"/>
<img src="https://img.shields.io/badge/CLI-000000?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=111" alt="CLI"/>
<img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white&labelColor=111" alt="Linux"/>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    SANCTUARY / QUOTES                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="40" viewBox="0 0 420 40" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    sanctuary
  </text>
  <line x1="90" y1="34" x2="330" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<!-- quotes -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    scripture from the machine
  </text>
</svg>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quotes" style="max-width:600px; filter:grayscale(0.7);" />

<br><br>

<!-- jokes -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    riddles from the void
  </text>
</svg>

<img src="https://readme-jokes.vercel.app/api?theme=gray&hideBorder&bgColor=0d0d0d&qColor=aaa&aColor=fff&textColor=888" alt="dev jokes" style="max-width:500px; filter:grayscale(0.8);" />

<br><br>

<!-- 3D contributions (will auto-generate after push) -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    depths of the deep
  </text>
</svg>

<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/main/profile-3d-contrib/profile-green-animate.svg" alt="3d contributions" style="max-width:600px; filter:grayscale(1);" />

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     CHAPEL / CONNECT                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="12">
    chapel
  </text>
  <line x1="85" y1="34" x2="315" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<a href="https://discord.gg/ZHOIKA">
  <img src="https://img.shields.io/badge/Discord-000?style=for-the-badge&logo=discord&logoColor=white&labelColor=111" alt="Discord"/>
</a>
<a href="https://t.me/ZHOIKA">
  <img src="https://img.shields.io/badge/Telegram-000?style=for-the-badge&logo=telegram&logoColor=white&labelColor=111" alt="Telegram"/>
</a>
<a href="https://github.com/ZHOIKA">
  <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white&labelColor=111" alt="GitHub"/>
</a>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                        FOOTER                              -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="480" height="100" viewBox="0 0 480 100" xmlns="http://www.w3.org/2000/svg">

  <!-- footer twinkling stars -->
  <text x="60" y="22" fill="white" font-size="7" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="4s" repeatCount="indefinite" begin="0s"/>
  </text>
  <text x="400" y="18" fill="white" font-size="8" font-family="Georgia" opacity="0">
    ✦
    <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="5s" repeatCount="indefinite" begin="1.2s"/>
  </text>
  <text x="240" y="12" fill="white" font-size="6" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
  </text>
  <text x="340" y="28" fill="white" font-size="5" font-family="Georgia" opacity="0">
    ✧
    <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4.2s" repeatCount="indefinite" begin="0.8s"/>
  </text>
  <text x="140" y="30" fill="white" font-size="7" font-family="Georgia" opacity="0">
    ✦
    <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="4.8s" repeatCount="indefinite" begin="3s"/>
  </text>

  <!-- orbit ring -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 240 42" to="360 240 42" dur="14s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="42" rx="56" ry="16" fill="none" stroke="white" stroke-width="0.35" opacity="0.08"/>
  </g>

  <circle cx="240" cy="42" r="5" fill="white" opacity="0.05">
    <animate attributeName="opacity" values="0.08;0.35;0.08" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="5;8;5" dur="3s" repeatCount="indefinite"/>
  </circle>

  <text x="240" y="78" fill="white" opacity="0.06" font-size="11" text-anchor="middle" font-family="Georgia">✟</text>
</svg>

<br>

<p style="font-family:'Courier New', monospace; font-size:10px; color:#1a1a1a; letter-spacing:6px; text-transform:uppercase;">
  ✦ Z H O I K A · M M X X V I ✦
</p>

<p style="font-family:Georgia, serif; font-size:11px; color:#111; font-style:italic; letter-spacing:2px;">
  even fallen angels can write their own heaven
</p>

<br>

<img src="https://komarev.com/ghpvc/?username=ZHOIKA&color=333333&style=flat&label=visitors&abbreviated=true" alt="visitors" style="filter:grayscale(1); opacity:0.15;" />

</div>

