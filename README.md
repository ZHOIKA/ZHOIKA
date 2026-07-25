
```markdown
<div align="center">

<!-- ════════════════════════════════════════════════════════════ -->
<!--              ANGELCORE HEADER — ANGEL WINGS SVG             -->
<!--  SMIL animations (animate, animateTransform) work on GitHub  -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="550" height="280" viewBox="0 0 550 280" xmlns="http://www.w3.org/2000/svg">

  <!-- Glow de fundo central -->
  <ellipse cx="275" cy="120" rx="110" ry="85" fill="white" opacity="0.015">
    <animate attributeName="opacity" values="0.015;0.05;0.015" dur="5s" repeatCount="indefinite"/>
  </ellipse>

  <!-- ≡≡≡ ESTRELAS E BRILHOS EM LOOP ≡≡≡ -->
  <g>
    <text x="70" y="45" fill="white" font-size="12" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0.9;0.9;0" dur="4s" repeatCount="indefinite" begin="0s"/>
    </text>
    <text x="160" y="30" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0.7;0.7;0" dur="3.5s" repeatCount="indefinite" begin="0.8s"/>
    </text>
    <text x="430" y="35" fill="white" font-size="13" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0.95;0.95;0" dur="5s" repeatCount="indefinite" begin="1.5s"/>
    </text>
    <text x="350" y="22" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0.6;0.6;0" dur="4.2s" repeatCount="indefinite" begin="0.4s"/>
    </text>
    <text x="480" y="60" fill="white" font-size="10" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0.8;0.8;0" dur="4.8s" repeatCount="indefinite" begin="2.2s"/>
    </text>
    <text x="40" y="85" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0.65;0.65;0" dur="3.8s" repeatCount="indefinite" begin="2s"/>
    </text>
  </g>

  <!-- ≡≡≡ COMETAS / ESTRELAS CADENTES ≡≡≡ -->
  <g>
    <line x1="50" y1="20" x2="95" y2="65" stroke="white" stroke-width="0.8" opacity="0">
      <animate attributeName="opacity" values="0;0.85;0" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
      <animate attributeName="x1" values="50;140" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
      <animate attributeName="y1" values="20;110" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
      <animate attributeName="x2" values="95;185" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
      <animate attributeName="y2" values="65;155" dur="3.2s" repeatCount="indefinite" begin="0.5s"/>
    </line>
    <line x1="490" y1="25" x2="445" y2="70" stroke="white" stroke-width="0.8" opacity="0">
      <animate attributeName="opacity" values="0;0.75;0" dur="4.2s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="x1" values="490;385" dur="4.2s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="y1" values="25;98" dur="4.2s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="x2" values="445;340" dur="4.2s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="y2" values="70;143" dur="4.2s" repeatCount="indefinite" begin="1.8s"/>
    </line>
  </g>

  <!-- ≡≡≡ AURÉOLA PULSANTE ≡≡≡ -->
  <ellipse cx="275" cy="50" rx="42" ry="11" fill="none" stroke="white" stroke-width="0.75" opacity="0.4">
    <animate attributeName="ry" values="11;15;11" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.25;0.7;0.25" dur="3s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="275" cy="50" rx="30" ry="8" fill="none" stroke="white" stroke-width="0.4" opacity="0.2">
    <animate attributeName="ry" values="8;11;8" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.1;0.4;0.1" dur="3s" repeatCount="indefinite"/>
  </ellipse>

  <!-- ≡≡≡ ASAS DE ANJO ANIMADAS (SEM FUNDO / TRANSPARENTES) ≡≡≡ -->
  <!-- Asa Esquerda -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="0 275 120; -7 275 120; 0 275 120" dur="3.2s" repeatCount="indefinite" />
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-4; 0,0" dur="3.2s" repeatCount="indefinite" additive="sum"/>
    <path d="M275 120 Q200 25 100 40 Q45 50 12 92 Q-2 122 0 148 Q16 128 55 115 Q95 102 140 94 L275 120Z" fill="white" opacity="0.18"/>
    <path d="M275 120 Q205 35 122 45 Q66 55 33 92 Q20 112 17 138 Q33 122 66 110 Q100 98 145 90 L275 120Z" fill="white" opacity="0.38"/>
    <path d="M275 120 Q210 45 144 52 Q94 60 61 95 Q47 110 42 128 Q64 114 91 104 Q124 92 163 84 L275 120Z" fill="white" opacity="0.68"/>
    <path d="M275 120 Q225 58 175 64 Q135 70 102 96 Q90 108 85 120 Q102 110 125 102 Q152 92 185 86 L275 120Z" fill="white" opacity="0.88"/>
  </g>

  <!-- Asa Direita -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="0 275 120; 7 275 120; 0 275 120" dur="3.2s" repeatCount="indefinite" />
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-4; 0,0" dur="3.2s" repeatCount="indefinite" additive="sum"/>
    <path d="M275 120 Q350 25 450 40 Q505 50 538 92 Q552 122 550 148 Q534 128 495 115 Q455 102 410 94 L275 120Z" fill="white" opacity="0.18"/>
    <path d="M275 120 Q345 35 428 45 Q484 55 517 92 Q530 112 533 138 Q517 122 484 110 Q450 98 405 90 L275 120Z" fill="white" opacity="0.38"/>
    <path d="M275 120 Q340 45 406 52 Q456 60 489 95 Q503 110 508 128 Q486 114 459 104 Q426 92 387 84 L275 120Z" fill="white" opacity="0.68"/>
    <path d="M275 120 Q325 58 375 64 Q415 70 448 96 Q460 108 465 120 Q448 110 425 102 Q398 92 365 86 L275 120Z" fill="white" opacity="0.88"/>
  </g>

  <!-- Núcleo de Luz Central -->
  <circle cx="275" cy="120" r="4" fill="white" opacity="0.8">
    <animate attributeName="r" values="3;6;3" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>

  <!-- ≡≡≡ TÍTULO ZHOIKA ≡≡≡ -->
  <text x="275" y="215" fill="white" font-size="36" text-anchor="middle" font-family="Georgia, 'Times New Roman', serif" letter-spacing="12" opacity="0.9">
    ZHOIKA
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- Subtítulo -->
  <text x="275" y="245" fill="white" font-size="10" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="12" opacity="0.3">
    ET LVX IN TENEBRIS LVCET
    <animate attributeName="opacity" values="0.15;0.45;0.15" dur="5s" repeatCount="indefinite"/>
  </text>

</svg>

<br>

<!-- Tagline -->
<svg width="480" height="42" viewBox="0 0 480 42" xmlns="http://www.w3.org/2000/svg">
  <text x="240" y="28" fill="white" opacity="0.45" font-size="14" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    <animate attributeName="opacity" values="0.45;0.18;0.45" dur="4s" repeatCount="indefinite"/>
    ✦ fallen angels write their own heaven ✦
  </text>
</svg>

<br>

<!-- Divider ornament -->
<svg width="320" height="30" viewBox="0 0 320 30" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="15" x2="300" y2="15" stroke="white" stroke-width="0.3" opacity="0.1"/>
  <circle cx="160" cy="15" r="3" fill="white" opacity="0.18">
    <animate attributeName="opacity" values="0.12;0.55;0.12" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <text x="140" y="14" fill="white" font-size="7" opacity="0.08" font-family="Georgia">✧</text>
  <text x="175" y="14" fill="white" font-size="7" opacity="0.08" font-family="Georgia">✧</text>
</svg>

</div>

<br>

<!-- ════════════════════════════════════════════════════════════ -->
<!--              PAC-MAN CONTRIBUTION ANIMATION                  -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="34" viewBox="0 0 360 34" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="20" fill="white" opacity="0.3" font-size="12" text-anchor="middle" font-family="Georgia, serif" letter-spacing="7" text-transform="uppercase">
    ✧ ouroboros
  </text>
  <line x1="60" y1="30" x2="300" y2="30" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/pacman-output/pacman-contribution-graph-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/pacman-output/pacman-contribution-graph.svg" />
  <img alt="pacman devouring contributions" src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/pacman-contribution-graph.svg" width="100%" style="max-width: 800px; filter: grayscale(0.4);" />
</picture>

</div>

<br>

<!-- ════════════════════════════════════════════════════════════ -->
<!--                    GITANIMALS                                -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="34" viewBox="0 0 360 34" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="20" fill="white" opacity="0.3" font-size="12" text-anchor="middle" font-family="Georgia, serif" letter-spacing="7" text-transform="uppercase">
    ✧ familiar spirits
  </text>
  <line x1="60" y1="30" x2="300" y2="30" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br><br>

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/ZHOIKA" width="100%" height="110" style="max-width: 800px; filter: grayscale(0.6);" alt="git animals" />
</a>

<br>

<svg width="360" height="20" viewBox="0 0 360 20" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="14" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    creatures born from the depth of commits
  </text>
</svg>

</div>

<br>

<!-- ════════════════════════════════════════════════════════════ -->
<!--                   SNAKE CONTRIBUTION                         -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="34" viewBox="0 0 360 34" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="20" fill="white" opacity="0.3" font-size="12" text-anchor="middle" font-family="Georgia, serif" letter-spacing="7" text-transform="uppercase">
    ✧ serpent
  </text>
  <line x1="60" y1="30" x2="300" y2="30" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" />
  <img alt="snake eating contributions" src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" width="100%" style="max-width: 800px; filter: grayscale(0.4);" />
</picture>

<br>

<svg width="360" height="20" viewBox="0 0 360 20" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="14" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    the serpent consumes the grid
  </text>
</svg>

</div>

<br>

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                   GRIMOIRE — PROJECT CARDS                   -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="42" viewBox="0 0 400 42" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ grimoire
  </text>
  <line x1="100" y1="36" x2="300" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

</div>

<table align="center" style="border-collapse: separate; border-spacing: 0 18px; max-width: 720px; margin: 0 auto;">
<tr>
<td style="border: 1px solid rgba(255,255,255,0.05); border-radius: 12px; padding: 24px 30px; background: rgba(255,255,255,0.012); width: 680px;">

<svg width="420" height="24" viewBox="0 0 420 24" xmlns="http://www.w3.org/2000/svg">
  <text x="10" y="18" fill="white" opacity="0.8" font-size="16" font-family="Georgia, serif" letter-spacing="4" font-style="italic">Zyro</text>
</svg>

<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #444; letter-spacing: 1px;">Android · Kotlin · Discord</span>

<p style="font-family: Georgia, serif; color: #777; font-size: 14px; line-height: 1.7; font-style: italic; margin-top: 8px;">
  Personalize sua presença no Discord com estilo, controle e uma experiência moderna no Android.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/Zyro" style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; text-decoration: none; letter-spacing: 2px;">
    <svg width="150" height="20" viewBox="0 0 150 20" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="14" fill="#555" font-size="12" font-family="'Courier New', monospace" letter-spacing="2">explore the abyss ››</text>
    </svg>
  </a>
</div>

</td>
</tr>
<tr>
<td style="border: 1px solid rgba(255,255,255,0.05); border-radius: 12px; padding: 24px 30px; background: rgba(255,255,255,0.012); width: 680px;">

<svg width="420" height="24" viewBox="0 0 420 24" xmlns="http://www.w3.org/2000/svg">
  <text x="10" y="18" fill="white" opacity="0.8" font-size="16" font-family="Georgia, serif" letter-spacing="4" font-style="italic">ZYRO-CLI</text>
</svg>

<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #444; letter-spacing: 1px;">CLI · Automation · Power</span>

<p style="font-family: Georgia, serif; color: #777; font-size: 14px; line-height: 1.7; font-style: italic; margin-top: 8px;">
  The command-line incarnation of Zyro's spirit — dark, fast, and elegant.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/ZYRO-CLI" style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; text-decoration: none; letter-spacing: 2px;">
    <svg width="160" height="20" viewBox="0 0 160 20" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="14" fill="#555" font-size="12" font-family="'Courier New', monospace" letter-spacing="2">invoke the terminal ››</text>
    </svg>
  </a>
</div>

</td>
</tr>
</table>

<br>

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                  CELESTIAL LEDGER — STATS                     -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="460" height="42" viewBox="0 0 460 42" xmlns="http://www.w3.org/2000/svg">
  <text x="230" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ celestial ledger
  </text>
  <line x1="110" y1="36" x2="350" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=ZHOIKA&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&icon_color=ffffff&border_radius=8&count_private=true&include_all_commits=true&hide_title=true" alt="github stats" style="max-width: 450px;" />

<br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZHOIKA&layout=compact&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&border_radius=8&hide_title=true" alt="top langs" style="max-width: 400px;" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ZHOIKA&bg_color=0a0a0a&color=ffffff&line=ffffff&point=555555&area=true&area_color=ffffff&hide_border=true&radius=4&custom_title=Contribution+Graph" alt="contribution graph" style="max-width: 100%; filter: grayscale(0.3);" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ZHOIKA&hide_border=true&background=0d0d0d&stroke=ffffff&ring=ffffff&fire=ffffff&currStreakNum=ffffff&sideNums=aaaaaa&currStreakLabel=ffffff&sideLabels=888888&dates=666666" alt="streak" style="max-width: 450px;" />

</div>

<br>

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                  RELIQUARY — TROPHY CASE                      -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="42" viewBox="0 0 420 42" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ reliquary
  </text>
  <line x1="95" y1="36" x2="325" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=ZHOIKA&theme=flat&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8&title=Stars,Followers,Commits,PullRequest,Issues,Repositories" alt="github trophy" style="max-width: 100%; filter: grayscale(0.9);" />

<br>

<svg width="380" height="20" viewBox="0 0 380 20" xmlns="http://www.w3.org/2000/svg">
  <text x="190" y="14" fill="white" opacity="0.08" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="4" font-style="italic">
    trophies from the unseen war
  </text>
</svg>

</div>

<br>

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                    ARMAMENT — SKILLS                          -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="42" viewBox="0 0 400 42" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ armament
  </text>
  <line x1="85" y1="36" x2="315" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
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

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                  SANCTUARY — WIDGETS & QUOTES                 -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="42" viewBox="0 0 420 42" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ sanctuary
  </text>
  <line x1="90" y1="36" x2="330" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<!-- Quotes from the machine -->
<svg width="440" height="28" viewBox="0 0 440 28" xmlns="http://www.w3.org/2000/svg">
  <text x="220" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    ❝ scripture from the machine ❞
  </text>
</svg>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quote" style="max-width: 600px; filter: grayscale(0.7);" />

<br><br>

<!-- Hymns / Spotify -->
<svg width="440" height="28" viewBox="0 0 440 28" xmlns="http://www.w3.org/2000/svg">
  <text x="220" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    ❝ hymns from the abyss ❞
  </text>
</svg>

<br>

<img src="https://spotify-github-profile.vercel.app/api/view?uid=ZHOIKA&cover_image=true&theme=default&show_offline=true&background_color=0d0d0d&interchange=true&bar_color=ffffff&bar_color_cover=false" alt="spotify" style="max-width: 400px; filter: grayscale(0.6); border-radius: 8px;" />

<br><br>

<!-- Gambits / Chess -->
<svg width="440" height="28" viewBox="0 0 440 28" xmlns="http://www.w3.org/2000/svg">
  <text x="220" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    ❝ gambits & shadows ❞
  </text>
</svg>

<br>

<a href="https://www.chess.com/member/ZHOIKA">
  <img src="https://img.shields.io/badge/CHESS.COM-000000?style=for-the-badge&logo=chess.com&logoColor=white&labelColor=111" alt="chess.com" style="filter: grayscale(1); opacity: 0.6;" />
</a>

<br><br>

<!-- 3D Contributions -->
<svg width="440" height="28" viewBox="0 0 440 28" xmlns="http://www.w3.org/2000/svg">
  <text x="220" y="18" fill="white" opacity="0.18" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="4">
    ❝ depths of the deep ❞
  </text>
</svg>

<br>

<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/main/profile-3d-contrib/profile-green-animate.svg" alt="3d contributions" style="max-width: 600px; filter: grayscale(1);" />

</div>

<br>

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                    CHAPEL — SOCIAL LINKS                      -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="42" viewBox="0 0 400 42" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="24" fill="white" opacity="0.5" font-size="15" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ chapel
  </text>
  <line x1="85" y1="36" x2="315" y2="36" stroke="white" stroke-width="0.3" opacity="0.1"/>
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

<hr style="border: none; border-top: 0.5px solid rgba(255,255,255,0.06);">

<!-- ════════════════════════════════════════════════════════════ -->
<!--                       FOOTER                                  -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="500" height="120" viewBox="0 0 500 120" xmlns="http://www.w3.org/2000/svg">

  <g>
    <text x="70" y="25" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.55;0.55;0" dur="5s" repeatCount="indefinite" begin="0s"/>
    </text>
    <text x="410" y="22" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="6s" repeatCount="indefinite" begin="1.5s"/>
    </text>
    <text x="245" y="15" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4s" repeatCount="indefinite" begin="2.5s"/>
    </text>
  </g>

  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 250 50" to="360 250 50" dur="16s" repeatCount="indefinite"/>
    <ellipse cx="250" cy="50" rx="60" ry="18" fill="none" stroke="white" stroke-width="0.35" opacity="0.06"/>
  </g>

  <circle cx="250" cy="50" r="6" fill="none" stroke="white" stroke-width="0.5" opacity="0.15">
    <animate attributeName="r" values="6;12;6" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.15;0.35;0.15" dur="3s" repeatCount="indefinite"/>
  </circle>

  <text x="250" y="92" fill="white" opacity="0.06" font-size="11" text-anchor="middle" font-family="Georgia">✟</text>
</svg>

<br>

<p style="font-family: 'Courier New', monospace; font-size: 11px; color: #181818; letter-spacing: 7px; text-transform: uppercase;">
  ✦ Z H O I K A · M M X X V I ✦
</p>

<p style="font-family: Georgia, serif; font-size: 12px; color: #0d0d0d; font-style: italic; letter-spacing: 2px;">
  even fallen angels can write their own heaven
</p>

<br>

<!-- devotional text -->
<details style="border: none; outline: none;">
<summary style="list-style: none; cursor: default; color: #1a1a1a; font-family: 'Courier New', monospace; font-size: 9px; letter-spacing: 3px; text-transform: uppercase; opacity: 0.5;">
  ✧ sententiae perpetuae ✧
</summary>
<p style="color: #222; font-family: Georgia, serif; font-size: 10px; letter-spacing: 3px; text-transform: uppercase; opacity: 0.4; font-style: italic;">
  et lux in tenebris lucet · tenebrae factae sunt · ex machina · de profundis · ad astra per aspera · memento mori · carpe noctem
</p>
</details>

<br>

<img src="https://komarev.com/ghpvc/?username=ZHOIKA&color=333333&style=flat&label=visitors&abbreviated=true" alt="visitors" style="filter: grayscale(1); opacity: 0.12;" />

</div>

```
