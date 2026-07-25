<div align="center">

<!-- ════════════════════════════════════════════ -->
<!--               ANGELCORE HEADER               -->
<!-- ════════════════════════════════════════════ -->

<svg width="420" height="180" viewBox="0 0 420 180" xmlns="http://www.w3.org/2000/svg">

  <!-- shooting stars -->
  <g>
    <line x1="20" y1="10" x2="45" y2="35" stroke="white" stroke-width="0.7" opacity="0">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x1" values="20;90" dur="4s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y1" values="10;80" dur="4s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x2" values="45;115" dur="4s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="y2" values="35;105" dur="4s" repeatCount="indefinite" begin="0s"/>
    </line>
    <line x1="380" y1="15" x2="355" y2="40" stroke="white" stroke-width="0.7" opacity="0">
      <animate attributeName="opacity" values="0;0.6;0" dur="5s" repeatCount="indefinite" begin="1.2s"/>
      <animate attributeName="x1" values="380;300" dur="5s" repeatCount="indefinite" begin="1.2s"/>
      <animate attributeName="y1" values="15;80" dur="5s" repeatCount="indefinite" begin="1.2s"/>
      <animate attributeName="x2" values="355;275" dur="5s" repeatCount="indefinite" begin="1.2s"/>
      <animate attributeName="y2" values="40;105" dur="5s" repeatCount="indefinite" begin="1.2s"/>
    </line>
    <line x1="300" y1="5" x2="320" y2="25" stroke="white" stroke-width="0.6" opacity="0">
      <animate attributeName="opacity" values="0;0.5;0" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
      <animate attributeName="x1" values="300;250" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
      <animate attributeName="y1" values="5;40" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
      <animate attributeName="x2" values="320;270" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
      <animate attributeName="y2" values="25;60" dur="3.5s" repeatCount="indefinite" begin="2.5s"/>
    </line>
  </g>

  <!-- floating particles -->
  <g>
    <circle cx="40" cy="100" r="1.5" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.5;0" dur="3s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="cy" values="100;70;100" dur="3s" repeatCount="indefinite" begin="0s"/>
    </circle>
    <circle cx="75" cy="130" r="1" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.35;0" dur="4s" repeatCount="indefinite" begin="0.7s"/>
      <animate attributeName="cy" values="130;95;130" dur="4s" repeatCount="indefinite" begin="0.7s"/>
    </circle>
    <circle cx="350" cy="110" r="1.2" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.4;0" dur="3.7s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="cy" values="110;78;110" dur="3.7s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
    <circle cx="390" cy="90" r="0.8" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.3;0" dur="3.2s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="cy" values="90;60;90" dur="3.2s" repeatCount="indefinite" begin="2s"/>
    </circle>
    <circle cx="120" cy="140" r="1.1" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.25;0" dur="4.5s" repeatCount="indefinite" begin="1s"/>
      <animate attributeName="cy" values="140;100;140" dur="4.5s" repeatCount="indefinite" begin="1s"/>
    </circle>
    <circle cx="300" cy="140" r="0.9" fill="white" opacity="0">
      <animate attributeName="opacity" values="0;0.3;0" dur="3.8s" repeatCount="indefinite" begin="0.3s"/>
      <animate attributeName="cy" values="140;105;140" dur="3.8s" repeatCount="indefinite" begin="0.3s"/>
    </circle>
  </g>

  <!-- left wing -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-7; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M210 85 Q160 20 90 30 Q50 38 20 70 Q8 92 10 112 Q22 96 50 88 Q80 78 110 72 L210 85Z" fill="white" opacity="0.06"/>
    <path d="M210 85 Q165 30 105 38 Q65 46 38 72 Q28 88 24 106 Q38 94 62 85 Q92 74 122 68 L210 85Z" fill="white" opacity="0.1"/>
    <path d="M210 85 Q172 40 120 46 Q82 52 55 74 Q44 86 40 100 Q56 90 75 82 Q100 72 130 66 L210 85Z" fill="white" opacity="0.16"/>
    <path d="M210 85 M178 48 Q140 26 95 32 Q62 38 38 58 Q28 68 22 80 Q32 70 52 62 Q78 52 108 46 L210 85Z" fill="white" opacity="0.08"/>
  </g>

  <!-- right wing -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,7; 0,0" dur="3s" repeatCount="indefinite"/>
    <path d="M210 85 Q260 20 330 30 Q370 38 400 70 Q412 92 410 112 Q398 96 370 88 Q340 78 310 72 L210 85Z" fill="white" opacity="0.06"/>
    <path d="M210 85 Q255 30 315 38 Q355 46 382 72 Q392 88 396 106 Q382 94 358 85 Q328 74 298 68 L210 85Z" fill="white" opacity="0.1"/>
    <path d="M210 85 Q248 40 300 46 Q338 52 365 74 Q376 86 380 100 Q364 90 345 82 Q320 72 290 66 L210 85Z" fill="white" opacity="0.16"/>
    <path d="M210 85 M242 48 Q280 26 325 32 Q358 38 382 58 Q392 68 398 80 Q388 70 368 62 Q342 52 312 46 L210 85Z" fill="white" opacity="0.08"/>
  </g>

  <!-- pulsing halo -->
  <circle cx="210" cy="85" r="38" fill="none" stroke="white" stroke-width="0.6" opacity="0.3">
    <animate attributeName="r" values="38;48;38" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="210" cy="85" r="28" fill="none" stroke="white" stroke-width="0.4" opacity="0.2">
    <animate attributeName="r" values="28;36;28" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.5;0.2" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="210" cy="85" r="15" fill="white" opacity="0.04">
    <animate attributeName="r" values="15;20;15" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.04;0.1;0.04" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- orbiting rings -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 210 42" to="360 210 42" dur="14s" repeatCount="indefinite"/>
    <ellipse cx="210" cy="42" rx="42" ry="12" fill="none" stroke="white" stroke-width="0.5" opacity="0.15"/>
    <ellipse cx="210" cy="42" rx="34" ry="9" fill="none" stroke="white" stroke-width="0.3" opacity="0.08"/>
  </g>

  <g>
    <animateTransform attributeName="transform" type="rotate" from="360 210 42" to="0 210 42" dur="18s" repeatCount="indefinite"/>
    <ellipse cx="210" cy="42" rx="50" ry="14" fill="none" stroke="white" stroke-width="0.4" opacity="0.1"/>
  </g>

  <!-- typing text animation -->
  <g>
    <text x="210" y="140" fill="white" opacity="0.8" font-size="18" text-anchor="middle" font-family="Georgia, serif" letter-spacing="4">
      ZHOIKA
      <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="210" y="158" fill="white" opacity="0.3" font-size="9" text-anchor="middle" font-family="Courier New, monospace" letter-spacing="6">
      ET LUX IN TENEBRIS LUCET
      <animate attributeName="opacity" values="0.2;0.5;0.2" dur="3s" repeatCount="indefinite"/>
    </text>
  </g>

</svg>

<br><br>

<!-- ════════════════════════════════════════════ -->
<!--              TYPING ANIMATION                -->
<!-- ════════════════════════════════════════════ -->

<svg width="420" height="36" viewBox="0 0 420 36" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="24" fill="white" opacity="0.6" font-size="13" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    <animate attributeName="opacity" values="0.6;0.3;0.6" dur="2s" repeatCount="indefinite"/>
    ✦ fallen angels write their own heaven ✦
  </text>
</svg>

<br>

<!-- ════════════════════════════════════════════ -->
<!--                 DIVIDER                      -->
<!-- ════════════════════════════════════════════ -->

<svg width="280" height="20" viewBox="0 0 280 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="10" y1="10" x2="270" y2="10" stroke="white" stroke-width="0.3" opacity="0.15"/>
  <circle cx="140" cy="10" r="3" fill="white" opacity="0.2">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br>

<!-- ════════════════════════════════════════════ -->
<!--              SNAKE GAME MINI                 -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 6px; text-transform: uppercase; font-size: 14px; border-bottom: 0.5px solid rgba(255,255,255,0.08); display: inline-block; padding-bottom: 5px;">
  🐍 ouroboros
</h2>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" />
  <img alt="snake game eating contributions" src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/output/github-contribution-grid-snake.svg" width="100%" style="max-width: 800px;" />
</picture>

</div>

<br>

<!-- ════════════════════════════════════════════ -->
<!--              GITANIMALS                      -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<p style="font-family: Georgia, serif; color: #666; font-style: italic; font-size: 12px; letter-spacing: 2px;">
  🐾 celestial pets born from commits
</p>

<br>

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/ZHOIKA" width="100%" height="120" style="max-width: 800px; filter: grayscale(0.5);" alt="gitanimals" />
</a>

</div>

<br>

---

<!-- ════════════════════════════════════════════ -->
<!--               GRIMOIRE / PROJECTS             -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ grimoire ✧
</h2>

<br><br>

</div>

<div style="border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; padding: 22px 28px; margin: 16px auto; background: rgba(255,255,255,0.015); max-width: 700px; transition: all 0.4s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.2)'; this.style.background='rgba(255,255,255,0.03)'; this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 30px rgba(0,0,0,0.4)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.06)'; this.style.background='rgba(255,255,255,0.015)'; this.style.transform='none'; this.style.boxShadow='none'">

<h3 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 3px; margin: 0 0 6px 0;">❝ Zyro ❞</h3>
<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; letter-spacing: 1px;">Android · Kotlin · Discord</span>

<p style="font-family: Georgia, serif; color: #888; font-size: 14px; line-height: 1.6; font-style: italic;">
  Personalize sua presenca no Discord com estilo, controle e uma experiencia moderna no Android.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/Zyro" style="font-family: 'Courier New', monospace; font-size: 12px; color: #666; text-decoration: none; letter-spacing: 1px;">[ explore the abyss >> ]</a>
</div>

</div>

<br>

<div style="border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; padding: 22px 28px; margin: 16px auto; background: rgba(255,255,255,0.015); max-width: 700px; transition: all 0.4s ease;"
     onmouseover="this.style.borderColor='rgba(255,255,255,0.2)'; this.style.background='rgba(255,255,255,0.03)'; this.style.transform='translateY(-3px)'; this.style.boxShadow='0 6px 30px rgba(0,0,0,0.4)'"
     onmouseout="this.style.borderColor='rgba(255,255,255,0.06)'; this.style.background='rgba(255,255,255,0.015)'; this.style.transform='none'; this.style.boxShadow='none'">

<h3 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 3px; margin: 0 0 6px 0;">❝ ZYRO-CLI ❞</h3>
<span style="font-family: 'Courier New', monospace; font-size: 11px; color: #555; letter-spacing: 1px;">CLI · Automation · Power</span>

<p style="font-family: Georgia, serif; color: #888; font-size: 14px; line-height: 1.6; font-style: italic;">
  The command-line incarnation of Zyro's spirit — dark, fast, and elegant.
</p>

<div align="right">
  <a href="https://github.com/ZHOIKA/ZYRO-CLI" style="font-family: 'Courier New', monospace; font-size: 12px; color: #666; text-decoration: none; letter-spacing: 1px;">[ invoke the terminal >> ]</a>
</div>

</div>

<br>

---

<!-- ════════════════════════════════════════════ -->
<!--           CELESTIAL LEDGER / STATS            -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ celestial ledger ✧
</h2>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=ZHOIKA&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&icon_color=ffffff&border_radius=8&count_private=true&include_all_commits=true&hide_title=true" alt="github stats" style="max-width: 450px;" />

<br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZHOIKA&layout=compact&hide_border=true&bg_color=0d0d0d&title_color=ffffff&text_color=aaaaaa&border_radius=8&hide_title=true" alt="top langs" style="max-width: 400px;" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ZHOIKA&bg_color=0a0a0a&color=ffffff&line=ffffff&point=555555&area=true&area_color=ffffff&hide_border=true&radius=4&custom_title=Contribution+Graph" alt="activity graph" style="max-width: 100%;" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ZHOIKA&hide_border=true&background=0d0d0d&stroke=ffffff&ring=ffffff&fire=ffffff&currStreakNum=ffffff&sideNums=aaaaaa&currStreakLabel=ffffff&sideLabels=888888&dates=666666" alt="streak" style="max-width: 450px;" />

</div>

<br>

---

<!-- ════════════════════════════════════════════ -->
<!--               TROPHY CASE                     -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ trophy case ✧
</h2>

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=ZHOIKA&theme=flat&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8&title=Stars,Followers,Commits,PullRequest,Issues,Repositories" alt="trophy" style="max-width: 100%; filter: grayscale(0.8);" />

</div>

<br>

---

<!-- ════════════════════════════════════════════ -->
<!--              ARSENAL / SKILLS                 -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ arsenal ✧
</h2>

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

<!-- ════════════════════════════════════════════ -->
<!--           MINI-GAMES & FUN WIDGETS           -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ arcade ✧
</h2>

<br><br>

<!-- Random Dev Quote -->
<svg width="420" height="30" viewBox="0 0 420 30" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.25" font-size="11" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    ❝ random scripture from the machine ❞
  </text>
</svg>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quote" style="max-width: 600px; filter: grayscale(0.7);" />

<br><br>

<!-- Random Joke -->
<svg width="420" height="30" viewBox="0 0 420 30" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.25" font-size="11" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    ❝ jokes from the void ❞
  </text>
</svg>

<img src="https://readme-jokes.vercel.app/api?theme=gray&hideBorder&bgColor=0d0d0d&qColor=aaa&aColor=fff&textColor=888" alt="jokes" style="max-width: 500px; filter: grayscale(0.8);" />

<br><br>

<!-- Spotify Now Playing -->
<svg width="420" height="30" viewBox="0 0 420 30" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.25" font-size="11" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    ❝ hymns from the abyss ❞
  </text>
</svg>

<img src="https://spotify-github-profile.vercel.app/api/view?uid=ZHOIKA&cover_image=true&theme=default&show_offline=true&background_color=0d0d0d&interchange=true&bar_color=ffffff&bar_color_cover=false" alt="spotify" style="max-width: 400px; filter: grayscale(0.5); border-radius: 8px;" />

<br>

<!-- Chess.com Stats -->
<svg width="420" height="30" viewBox="0 0 420 30" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.25" font-size="11" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    ❝ gambits & shadows ❞
  </text>
</svg>

<a href="https://www.chess.com/member/ZHOIKA">
  <img src="https://chess-temp-badge.vercel.app/api?username=ZHOIKA&theme=gray&style=for-the-badge&width=400" alt="chess.com stats" style="max-width: 400px; filter: grayscale(1); opacity: 0.7;" />
</a>

<br><br>

<!-- Penguin / 3D Contribution -->
<svg width="420" height="30" viewBox="0 0 420 30" xmlns="http://www.w3.org/2000/svg">
  <text x="210" y="18" fill="white" opacity="0.25" font-size="11" text-anchor="middle" font-family="Georgia, serif" font-style="italic" letter-spacing="2">
    ❝ contributions from the deep ❞
  </text>
</svg>

<img src="https://raw.githubusercontent.com/ZHOIKA/ZHOIKA/main/profile-3d-contrib/profile-green-animate.svg" alt="3d contributions" style="max-width: 600px; filter: grayscale(1);" />

</div>

<br>

---

<!-- ════════════════════════════════════════════ -->
<!--                 CONNECT                       -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<h2 style="font-family: Georgia, serif; color: #fff; font-weight: 300; letter-spacing: 8px; text-transform: uppercase; font-size: 15px; border-bottom: 0.5px solid rgba(255,255,255,0.1); display: inline-block; padding-bottom: 6px;">
  ✧ connect ✧
</h2>

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

<!-- ════════════════════════════════════════════ -->
<!--                 FOOTER                        -->
<!-- ════════════════════════════════════════════ -->

<div align="center">

<marquee behavior="scroll" direction="left" scrollamount="2" style="color: #2a2a2a; font-family: Georgia, serif; font-size: 10px; letter-spacing: 4px; text-transform: uppercase;">
  ✧ et lux in tenebris lucet ✧ · ✧ tenebrae factae sunt ✧ · ✧ ex machina ✧ · ✧ de profundis ✧ · ✧ ad astra per aspera ✧ · ✧ memento mori ✧ · ✧ carpe noctem ✧
</marquee>

<br>

<!-- Animated footer ornament -->
<svg width="160" height="70" viewBox="0 0 160 70" xmlns="http://www.w3.org/2000/svg">
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 80 28" to="360 80 28" dur="12s" repeatCount="indefinite"/>
    <ellipse cx="80" cy="28" rx="52" ry="16" fill="none" stroke="white" stroke-width="0.5" opacity="0.15"/>
    <ellipse cx="80" cy="28" rx="44" ry="12" fill="none" stroke="white" stroke-width="0.3" opacity="0.08"/>
  </g>
  <circle cx="80" cy="28" r="6" fill="white" opacity="0.06">
    <animate attributeName="opacity" values="0.1;0.4;0.1" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="5;8;5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="80" y="58" fill="white" opacity="0.08" font-size="10" text-anchor="middle" font-family="Georgia">✧</text>
</svg>

<br>

<p style="font-family: 'Courier New', monospace; font-size: 10px; color: #2a2a2a; letter-spacing: 5px; text-transform: uppercase;">
  ✦ Z H O I K A · M M X X V I ✦
</p>

<p style="font-family: Georgia, serif; font-size: 11px; color: #1a1a1a; font-style: italic; letter-spacing: 1px;">
  "even fallen angels can write their own heaven"
</p>

<br>

<img src="https://komarev.com/ghpvc/?username=ZHOIKA&color=333333&style=flat&label=visitors&abbreviated=true" alt="visitors" style="filter: grayscale(1); opacity: 0.2;" />

</div>

