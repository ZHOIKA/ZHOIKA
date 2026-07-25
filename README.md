<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ANGELCORE HEADER                      -->
<!--        estrelas que surgem do abismo e se apagam         -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="480" height="220" viewBox="0 0 480 220" xmlns="http://www.w3.org/2000/svg">

  <!-- deep background glow -->
  <ellipse cx="240" cy="110" rx="90" ry="70" fill="white" opacity="0.015">
    <animate attributeName="opacity" values="0.015;0.04;0.015" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="rx" values="90;110;90" dur="5s" repeatCount="indefinite"/>
  </ellipse>

  <!-- ✦ STARS THAT APPEAR, SHINE, THEN FADE ✦ -->
  <g>
    <text x="50" y="30" fill="white" font-size="10" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.7;0.7;0" dur="5s" repeatCount="indefinite" begin="0s"/>
    </text>
    <text x="140" y="18" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="4.2s" repeatCount="indefinite" begin="0.6s"/>
    </text>
    <text x="380" y="25" fill="white" font-size="11" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.8;0.8;0" dur="6s" repeatCount="indefinite" begin="1.2s"/>
    </text>
    <text x="300" y="15" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="3.8s" repeatCount="indefinite" begin="0.3s"/>
    </text>
    <text x="430" y="40" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="5.5s" repeatCount="indefinite" begin="2s"/>
    </text>
    <text x="25" y="60" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
    </text>
    <text x="220" y="22" fill="white" font-size="5" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="3.5s" repeatCount="indefinite" begin="0.9s"/>
    </text>
    <text x="450" y="60" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.55;0.55;0" dur="4.8s" repeatCount="indefinite" begin="2.5s"/>
    </text>
    <text x="100" y="50" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="3.2s" repeatCount="indefinite" begin="1.5s"/>
    </text>
    <text x="350" y="45" fill="white" font-size="5" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.3;0.3;0" dur="4s" repeatCount="indefinite" begin="3s"/>
    </text>
  </g>

  <!-- shooting stars that streak across -->
  <g>
    <line x1="30" y1="12" x2="60" y2="42" stroke="white" stroke-width="0.6" opacity="0">
      <animate attributeName="opacity" values="0;0.8;0" dur="3s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x1" values="30;100" dur="3s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y1" values="12;82" dur="3s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x2" values="60;130" dur="3s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y2" values="42;112" dur="3s" repeatCount="indefinite" begin="0s"/>
    </line>
    <line x1="440" y1="15" x2="410" y2="45" stroke="white" stroke-width="0.6" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="x1" values="440;360" dur="4s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="y1" values="15;70" dur="4s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="x2" values="410;330" dur="4s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="y2" values="45;100" dur="4s" repeatCount="indefinite" begin="1.5s"/>
    </line>
    <line x1="280" y1="8" x2="300" y2="28" stroke="white" stroke-width="0.5" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="3.5s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="x1" values="280;230" dur="3.5s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="y1" values="8;40" dur="3.5s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="x2" values="300;250" dur="3.5s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="y2" values="28;60" dur="3.5s" repeatCount="indefinite" begin="3s"/>
    </line>
  </g>

  <!-- left wing -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-8; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M240 105 Q185 30 100 40 Q55 48 25 82 Q12 108 15 130 Q28 112 60 102 Q95 90 130 84 L240 105Z" fill="white" opacity="0.05"/>
    <path d="M240 105 Q190 38 118 48 Q74 56 45 85 Q34 104 30 124 Q46 110 74 100 Q104 88 140 82 L240 105Z" fill="white" opacity="0.09"/>
    <path d="M240 105 Q195 48 135 54 Q94 62 65 88 Q52 102 48 118 Q66 106 88 97 Q116 86 150 80 L240 105Z" fill="white" opacity="0.14"/>
    <path d="M240 105 Q200 58 152 62 Q112 68 80 92 Q68 104 62 118 Q82 106 102 98 Q128 88 160 82 L240 105Z" fill="white" opacity="0.07"/>
  </g>

  <!-- right wing -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,8; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M240 105 Q295 30 380 40 Q425 48 455 82 Q468 108 465 130 Q452 112 420 102 Q385 90 350 84 L240 105Z" fill="white" opacity="0.05"/>
    <path d="M240 105 Q290 38 362 48 Q406 56 435 85 Q446 104 450 124 Q434 110 406 100 Q376 88 340 82 L240 105Z" fill="white" opacity="0.09"/>
    <path d="M240 105 Q285 48 345 54 Q386 62 415 88 Q428 102 432 118 Q414 106 392 97 Q364 86 330 80 L240 105Z" fill="white" opacity="0.14"/>
    <path d="M240 105 Q280 58 328 62 Q368 68 400 92 Q412 104 418 118 Q398 106 378 98 Q352 88 320 82 L240 105Z" fill="white" opacity="0.07"/>
  </g>

  <!-- pulsing halo -->
  <circle cx="240" cy="105" r="42" fill="none" stroke="white" stroke-width="0.5" opacity="0.25">
    <animate attributeName="r" values="42;55;42" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.25;0.6;0.25" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="240" cy="105" r="32" fill="none" stroke="white" stroke-width="0.35" opacity="0.15">
    <animate attributeName="r" values="32;42;32" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.15;0.4;0.15" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="240" cy="105" r="18" fill="white" opacity="0.035">
    <animate attributeName="r" values="18;24;18" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.035;0.09;0.035" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <!-- orbiting rings -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 240 55" to="360 240 55" dur="15s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="55" rx="48" ry="14" fill="none" stroke="white" stroke-width="0.4" opacity="0.12"/>
    <ellipse cx="240" cy="55" rx="38" ry="10" fill="none" stroke="white" stroke-width="0.25" opacity="0.06"/>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="360 240 55" to="0 240 55" dur="20s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="55" rx="58" ry="16" fill="none" stroke="white" stroke-width="0.3" opacity="0.08"/>
  </g>

  <!-- ZHOIKA text with letter animation -->
  <g>
    <text x="240" y="172" fill="white" font-size="28" text-anchor="middle" font-family="Georgia, 'Times New Roman', serif" letter-spacing="8" opacity="0.85">
      ZHOIKA
      <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- subtitle line with glow -->
  <text x="240" y="195" fill="white" font-size="9" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="10" opacity="0.3">
    ET LVX IN TENEBRIS LVCET
    <animate attributeName="opacity" values="0.2;0.5;0.2" dur="4s" repeatCount="indefinite"/>
  </text>

</svg>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              TAGLINE WITH FADE ANIMATION                 -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="460" height="40" viewBox="0 0 460 40" xmlns="http://www.w3.org/2000/svg">
  <text x="230" y="26" fill="white" opacity="0.5" font-size="13" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="3">
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="3s" repeatCount="indefinite"/>
    ✦ fallen angels write their own heaven ✦
  </text>
</svg>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ELEGANT DIVIDER                       -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="300" height="28" viewBox="0 0 300 28" xmlns="http://www.w3.org/2000/svg">
  <line x1="15" y1="14" x2="285" y2="14" stroke="white" stroke-width="0.3" opacity="0.12"/>
  <circle cx="150" cy="14" r="3" fill="white" opacity="0.2">
    <animate attributeName="opacity" values="0.15;0.6;0.15" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="130" y="13" fill="white" font-size="6" opacity="0.1" font-family="Georgia">✧</text>
  <text x="164" y="13" fill="white" font-size="6" opacity="0.1" font-family="Georgia">✧</text>
</svg>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              SNAKE / OUROBOROS SECTION                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="32" viewBox="0 0 360 32" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="18" fill="white" opacity="0.3" font-size="11" text-anchor="middle" font-family="Georgia, serif" letter-spacing="6" text-transform="uppercase">
    ✧ ouroboros
  </text>
  <line x1="60" y1="28" x2="300" y2="28" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" />
  <img alt="contribution serpent" src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" width="100%" style="max-width: 800px; filter: grayscale(0.3);" />
</picture>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   GITANIMALS                             -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="360" height="32" viewBox="0 0 360 32" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="18" fill="white" opacity="0.3" font-size="11" text-anchor="middle" font-family="Georgia, serif" letter-spacing="6" text-transform="uppercase">
    ✧ familiar spirits
  </text>
  <line x1="60" y1="28" x2="300" y2="28" stroke="white" stroke-width="0.2" opacity="0.06"/>
</svg>

<br>

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/ZHOIKA" width="100%" height="110" style="max-width: 800px; filter: grayscale(0.6);" alt="git animals" />
</a>

<br>

<svg width="340" height="18" viewBox="0 0 340 18" xmlns="http://www.w3.org/2000/svg">
  <text x="170" y="12" fill="white" opacity="0.12" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="3" font-style="italic">
    creatures born from the depth of commits
  </text>
</svg>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    GRIMOIRE / PROJECTS                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ grimoire
  </text>
  <line x1="100" y1="34" x2="300" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

</div>

<!-- Zyro card -->
<div style="border: 1px solid rgba(255,255,255,0.05); border-radius: 12px; padding: 24px 30px; margin: 18px auto; background: rgba(255,255,255,0.012); max-width: 700px; transition: border-color 0.6s ease, background 0.6s ease, transform 0.6s ease, box-shadow 0.6s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.18)'; this.style.background='rgba(255,255,255,0.025)'; this.style.transform='translateY(-4px)'; this.style.boxShadow='0 8px 40px rgba(0,0,0,0.5)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.05)'; this.style.background='rgba(255,255,255,0.012)'; this.style.transform='none'; this.style.boxShadow='none'">

<svg width="420" height="22" viewBox="0 0 420 22" xmlns="http://www.w3.org/2000/svg">
  <text x="10" y="16" fill="white" opacity="0.8" font-size="15" font-family="Georgia, serif" letter-spacing="4" font-style="italic">Zyro</text>
</svg>

<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #444; letter-spacing: 1px;">Android · Kotlin · Discord</span>

<p style="font-family: Georgia, serif; color: #777; font-size: 14px; line-height: 1.7; font-style: italic; margin-top: 8px;">
  Personalize sua presenca no Discord com estilo, controle e uma experiencia moderna no Android.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/Zyro" style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; text-decoration: none; letter-spacing: 2px;">
    <svg width="140" height="18" viewBox="0 0 140 18" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="13" fill="#555" font-size="11" font-family="'Courier New', monospace" letter-spacing="2">
        explore the abyss ››
      </text>
    </svg>
  </a>
</div>

</div>

<br>

<!-- ZYRO-CLI card -->
<div style="border: 1px solid rgba(255,255,255,0.05); border-radius: 12px; padding: 24px 30px; margin: 18px auto; background: rgba(255,255,255,0.012); max-width: 700px; transition: border-color 0.6s ease, background 0.6s ease, transform 0.6s ease, box-shadow 0.6s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.18)'; this.style.background='rgba(255,255,255,0.025)'; this.style.transform='translateY(-4px)'; this.style.boxShadow='0 8px 40px rgba(0,0,0,0.5)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.05)'; this.style.background='rgba(255,255,255,0.012)'; this.style.transform='none'; this.style.boxShadow='none'">

<svg width="420" height="22" viewBox="0 0 420 22" xmlns="http://www.w3.org/2000/svg">
  <text x="10" y="16" fill="white" opacity="0.8" font-size="15" font-family="Georgia, serif" letter-spacing="4" font-style="italic">ZYRO-CLI</text>
</svg>

<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #444; letter-spacing: 1px;">CLI · Automation · Power</span>

<p style="font-family: Georgia, serif; color: #777; font-size: 14px; line-height: 1.7; font-style: italic; margin-top: 8px;">
  The command-line incarnation of Zyro's spirit — dark, fast, and elegant.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/ZYRO-CLI" style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; text-decoration: none; letter-spacing: 2px;">
    <svg width="160" height="18" viewBox="0 0 160 18" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="13" fill="#555" font-size="11" font-family="'Courier New', monospace" letter-spacing="2">
        invoke the terminal ››
      </text>
    </svg>
  </a>
</div>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                 CELESTIAL LEDGER / STATS                  -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="460" height="40" viewBox="0 0 460 40" xmlns="http://www.w3.org/2000/svg">
  <text x="230" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ celestial ledger
  </text>
  <line x1="110" y1="34" x2="350" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
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

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    TROPHY CASE                            -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="40" viewBox="0 0 420 40" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ reliquary
  </text>
  <line x1="95" y1="34" x2="325" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=ZHOIKA&theme=flat&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8&title=Stars,Followers,Commits,PullRequest,Issues,Repositories" alt="github trophy" style="max-width: 100%; filter: grayscale(0.9);" />

<br>

<svg width="360" height="18" viewBox="0 0 360 18" xmlns="http://www.w3.org/2000/svg">
  <text x="180" y="12" fill="white" opacity="0.1" font-size="8" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="3" font-style="italic">
    trophies from the unseen war
  </text>
</svg>

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     ARSENAL / SKILLS                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ armament
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
<!--              SANCTUARY / QUOTES & WIDGETS                -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="420" height="40" viewBox="0 0 420 40" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ sanctuary
  </text>
  <line x1="90" y1="34" x2="330" y2="34" stroke="white" stroke-width="0.3" opacity="0.1"/>
</svg>

<br><br>

<!-- scripture -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.2" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="3">
    ❝ scripture from the machine ❞
  </text>
</svg>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quote" style="max-width: 600px; filter: grayscale(0.7);" />

<br><br>

<!-- hymns -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.2" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="3">
    ❝ hymns from the abyss ❞
  </text>
</svg>

<img src="https://spotify-github-profile.vercel.app/api/view?uid=ZHOIKA&cover_image=true&theme=default&show_offline=true&background_color=0d0d0d&interchange=true&bar_color=ffffff&bar_color_cover=false" alt="spotify" style="max-width: 400px; filter: grayscale(0.6); border-radius: 8px;" />

<br><br>

<!-- gambits -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.2" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="3">
    ❝ gambits & shadows ❞
  </text>
</svg>

<a href="https://www.chess.com/member/ZHOIKA">
  <img src="https://img.shields.io/badge/CHESS.COM-000000?style=for-the-badge&logo=chess.com&logoColor=white&labelColor=111" alt="chess.com" style="filter: grayscale(1); opacity: 0.6;" />
</a>

<br><br>

<!-- deep contributions -->
<svg width="420" height="28" viewBox="0 0 420 28" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.2" font-size="10" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="3">
    ❝ depths of the deep ❞
  </text>
</svg>

<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/main/profile-3d-contrib/profile-green-animate.svg" alt="3d contributions" style="max-width: 600px; filter: grayscale(1);" />

</div>

<br>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    CHAPEL / CONNECT                       -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="22" fill="white" opacity="0.5" font-size="14" text-anchor="middle" font-family="Georgia, serif" letter-spacing="10" text-transform="uppercase">
    ✦ chapel
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
<!--                       FOOTER                              -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="480" height="100" viewBox="0 0 480 100" xmlns="http://www.w3.org/2000/svg">

  <!-- footer stars -->
  <g>
    <text x="60" y="20" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="4s" repeatCount="indefinite" begin="0s"/>
    </text>
    <text x="400" y="18" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="5s" repeatCount="indefinite" begin="1s"/>
    </text>
    <text x="230" y="12" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="3.5s" repeatCount="indefinite" begin="2s"/>
    </text>
    <text x="340" y="25" fill="white" font-size="5" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4.2s" repeatCount="indefinite" begin="0.5s"/>
    </text>
    <text x="130" y="28" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="4.8s" repeatCount="indefinite" begin="2.5s"/>
    </text>
  </g>

  <!-- orbiting ring -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 240 42" to="360 240 42" dur="14s" repeatCount="indefinite"/>
    <ellipse cx="240" cy="42" rx="55" ry="16" fill="none" stroke="white" stroke-width="0.4" opacity="0.08"/>
  </g>
  <circle cx="240" cy="42" r="6" fill="white" opacity="0.05">
    <animate attributeName="opacity" values="0.08;0.35;0.08" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="5;8;5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="240" y="78" fill="white" opacity="0.07" font-size="10" text-anchor="middle" font-family="Georgia">✟</text>
</svg>

<br>

<p style="font-family: 'Courier New', monospace; font-size: 10px; color: #1a1a1a; letter-spacing: 6px; text-transform: uppercase;">
  ✦ Z H O I K A · M M X X V I ✦
</p>

<p style="font-family: Georgia, serif; font-size: 11px; color: #111; font-style: italic; letter-spacing: 2px;">
  even fallen angels can write their own heaven
</p>

<br>

<img src="https://komarev.com/ghpvc/?username=ZHOIKA&color=333333&style=flat&label=visitors&abbreviated=true" alt="visitors" style="filter: grayscale(1); opacity: 0.15;" />

</div>

