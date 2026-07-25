<div align="center">

<!-- ════════════════════════════════════════════════════════════ -->
<!--              ANGELCORE HEADER — INLINE SVG ANIMATIONS        -->
<!--  SMIL animations (animate, animateTransform) work on GitHub  -->
<!-- ════════════════════════════════════════════════════════════ -->

<svg width="500" height="260" viewBox="0 0 500 260" xmlns="http://www.w3.org/2000/svg">

  <!-- deep radiance -->
  <ellipse cx="250" cy="130" rx="100" ry="80" fill="white" opacity="0.012">
    <animate attributeName="opacity" values="0.012;0.05;0.012" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="rx" values="100;130;100" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="ry" values="80;100;80" dur="6s" repeatCount="indefinite"/>
  </ellipse>

  <!-- ≡≡≡  STARS THAT APPEAR, SHINE, THEN VANISH  ≡≡≡ -->
  <g>
    <text x="60" y="38" fill="white" font-size="11" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.8;0.8;0" dur="6s" repeatCount="indefinite" begin="0s"/>
    </text>
    <text x="150" y="22" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.55;0.55;0" dur="5s" repeatCount="indefinite" begin="0.8s"/>
    </text>
    <text x="390" y="30" fill="white" font-size="12" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.85;0.85;0" dur="7s" repeatCount="indefinite" begin="1.5s"/>
    </text>
    <text x="310" y="18" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="4.5s" repeatCount="indefinite" begin="0.4s"/>
    </text>
    <text x="445" y="50" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.65;0.65;0" dur="6.5s" repeatCount="indefinite" begin="2.2s"/>
    </text>
    <text x="30" y="75" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="5.5s" repeatCount="indefinite" begin="2s"/>
    </text>
    <text x="230" y="28" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.4;0.4;0" dur="4s" repeatCount="indefinite" begin="1.2s"/>
    </text>
    <text x="465" y="72" fill="white" font-size="10" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.6;0.6;0" dur="5.8s" repeatCount="indefinite" begin="3s"/>
    </text>
    <text x="110" y="62" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.42;0.42;0" dur="3.8s" repeatCount="indefinite" begin="1.8s"/>
    </text>
    <text x="360" y="55" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="5s" repeatCount="indefinite" begin="3.5s"/>
    </text>
    <text x="185" y="42" fill="white" font-size="9" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.55;0.55;0" dur="4.2s" repeatCount="indefinite" begin="0.6s"/>
    </text>
    <text x="420" y="20" fill="white" font-size="5" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.3;0.3;0" dur="3.2s" repeatCount="indefinite" begin="2.8s"/>
    </text>
  </g>

  <!-- ≡≡≡  SHOOTING STARS  ≡≡≡ -->
  <g>
    <line x1="40" y1="18" x2="75" y2="53" stroke="white" stroke-width="0.6" opacity="0">
      <animate attributeName="opacity" values="0;0.85;0" dur="3.5s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x1" values="40;120" dur="3.5s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y1" values="18;98" dur="3.5s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x2" values="75;155" dur="3.5s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y2" values="53;133" dur="3.5s" repeatCount="indefinite" begin="0s"/>
    </line>
    <line x1="455" y1="22" x2="420" y2="57" stroke="white" stroke-width="0.6" opacity="0">
      <animate attributeName="opacity" values="0;0.75;0" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="x1" values="455;360" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="y1" values="22;85" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="x2" values="420;325" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
      <animate attributeName="y2" values="57;120" dur="4.5s" repeatCount="indefinite" begin="1.8s"/>
    </line>
    <line x1="290" y1="12" x2="312" y2="34" stroke="white" stroke-width="0.5" opacity="0">
      <animate attributeName="opacity" values="0;0.65;0" dur="4s" repeatCount="indefinite" begin="3.5s"/>
      <animate attributeName="x1" values="290;230" dur="4s" repeatCount="indefinite" begin="3.5s"/>
      <animate attributeName="y1" values="12;50" dur="4s" repeatCount="indefinite" begin="3.5s"/>
      <animate attributeName="x2" values="312;252" dur="4s" repeatCount="indefinite" begin="3.5s"/>
      <animate attributeName="y2" values="34;72" dur="4s" repeatCount="indefinite" begin="3.5s"/>
    </line>
  </g>

  <!-- ≡≡≡  LEFT WING — BEATING  ≡≡≡ -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-9; 0,0" dur="3.5s" repeatCount="indefinite"/>
    <path d="M250 125 Q190 42 100 52 Q52 62 22 100 Q10 128 12 155 Q24 136 58 124 Q92 112 130 104 L250 125Z" fill="white" opacity="0.04"/>
    <path d="M250 125 Q195 50 122 58 Q76 68 46 102 Q34 124 30 148 Q48 132 78 120 Q108 108 148 100 L250 125Z" fill="white" opacity="0.08"/>
    <path d="M250 125 Q200 60 140 66 Q98 74 68 106 Q55 122 50 140 Q70 126 94 116 Q124 104 158 96 L250 125Z" fill="white" opacity="0.13"/>
    <path d="M250 125 M205 68 Q162 38 110 44 Q72 50 42 78 Q30 92 25 108 Q48 94 72 84 Q102 72 138 64 L250 125Z" fill="white" opacity="0.06"/>
  </g>

  <!-- ≡≡≡  RIGHT WING — BEATING (opposite phase)  ≡≡≡ -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,9; 0,0" dur="3.5s" repeatCount="indefinite"/>
    <path d="M250 125 Q310 42 400 52 Q448 62 478 100 Q490 128 488 155 Q476 136 442 124 Q408 112 370 104 L250 125Z" fill="white" opacity="0.04"/>
    <path d="M250 125 Q305 50 378 58 Q424 68 454 102 Q466 124 470 148 Q452 132 422 120 Q392 108 352 100 L250 125Z" fill="white" opacity="0.08"/>
    <path d="M250 125 Q300 60 360 66 Q402 74 432 106 Q445 122 450 140 Q430 126 406 116 Q376 104 342 96 L250 125Z" fill="white" opacity="0.13"/>
    <path d="M250 125 M295 68 Q338 38 390 44 Q428 50 458 78 Q470 92 475 108 Q452 94 428 84 Q398 72 362 64 L250 125Z" fill="white" opacity="0.06"/>
  </g>

  <!-- ≡≡≡  PULSING HALO  ≡≡≡ -->
  <circle cx="250" cy="125" r="44" fill="none" stroke="white" stroke-width="0.5" opacity="0.2">
    <animate attributeName="r" values="44;60;44" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.5;0.2" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="125" r="34" fill="none" stroke="white" stroke-width="0.35" opacity="0.12">
    <animate attributeName="r" values="34;46;34" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.12;0.35;0.12" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="125" r="20" fill="none" stroke="white" stroke-width="0.25" opacity="0.08">
    <animate attributeName="r" values="20;28;20" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.08;0.2;0.08" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="125" r="10" fill="white" opacity="0.03">
    <animate attributeName="r" values="10;15;10" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.03;0.08;0.03" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- ≡≡≡  ORBITING RINGS  ≡≡≡ -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 250 65" to="360 250 65" dur="18s" repeatCount="indefinite"/>
    <ellipse cx="250" cy="65" rx="55" ry="16" fill="none" stroke="white" stroke-width="0.4" opacity="0.1"/>
    <ellipse cx="250" cy="65" rx="44" ry="12" fill="none" stroke="white" stroke-width="0.25" opacity="0.05"/>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="360 250 65" to="0 250 65" dur="22s" repeatCount="indefinite"/>
    <ellipse cx="250" cy="65" rx="66" ry="18" fill="none" stroke="white" stroke-width="0.3" opacity="0.07"/>
  </g>

  <!-- ≡≡≡  ZHOIKA TITLE WITH GENTLE BREATHING  ≡≡≡ -->
  <text x="250" y="202" fill="white" font-size="34" text-anchor="middle" font-family="Georgia, 'Times New Roman', serif" letter-spacing="10" opacity="0.9">
    ZHOIKA
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- subtitle -->
  <text x="250" y="230" fill="white" font-size="10" text-anchor="middle" font-family="'Courier New', monospace" letter-spacing="12" opacity="0.28">
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
<!--  Uses the output branch — already generated & working        -->
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
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/pacman-contribution-graph-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/pacman-contribution-graph.svg" />
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
<!--  No onmouseover/onmouseout — GitHub strips JS event handlers -->
<!--  Pure CSS hover via inline <style> won't work either         -->
<!--  Using simple transparent cards with subtle existing borders -->
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
  Personalize sua presenca no Discord com estilo, controle e uma experiencia moderna no Android.
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

<!-- Snake Game (will appear after first workflow run) -->
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
<!--  No <marquee> — GitHub strips it. Using static text + SVGs    -->
<!-- ════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="500" height="120" viewBox="0 0 500 120" xmlns="http://www.w3.org/2000/svg">

  <!-- footer stars appearing and vanishing -->
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
    <text x="360" y="30" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.45;0.45;0" dur="4.8s" repeatCount="indefinite" begin="0.8s"/>
    </text>
    <text x="140" y="32" fill="white" font-size="8" font-family="Georgia" opacity="0">
      ✦
      <animate attributeName="opacity" values="0;0;0.5;0.5;0" dur="5.2s" repeatCount="indefinite" begin="3s"/>
    </text>
    <text x="440" y="35" fill="white" font-size="7" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.35;0.35;0" dur="3.5s" repeatCount="indefinite" begin="1.2s"/>
    </text>
    <text x="50" y="45" fill="white" font-size="6" font-family="Georgia" opacity="0">
      ✧
      <animate attributeName="opacity" values="0;0;0.3;0.3;0" dur="4.2s" repeatCount="indefinite" begin="0.5s"/>
    </text>
  </g>

  <!-- rotating ring -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 250 50" to="360 250 50" dur="16s" repeatCount="indefinite"/>
    <ellipse cx="250" cy="50" rx="60" ry="18" fill="none" stroke="white" stroke-width="0.35" opacity="0.06"/>
  </g>

  <!-- central pulse -->
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

<!-- devotional text — scrolls infinitely via pure CSS animation -->
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


