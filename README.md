<img width="800" height="320" alt="about" src="https://github.com/user-attachments/assets/857d77fe-f05c-4ad0-a9d6-03f0a5a00c27" /><img width="800" height="300" alt="header" src="https://github.com/user-attachments/assets/aee0f039-2514-4202-a534-3c77fb0912b1" />
<svg xmlns="http://www.w3.org/2000/svg" width="800" height="300" viewBox="0 0 800 300">
  <style>
    .name { animation: nameIn 11s ease-out infinite; }
    .underline { animation: underlineDraw 11s ease-out infinite; transform-origin: left center; }
    .meta { animation: fadeUp 11s ease-out infinite; animation-delay: 0.3s; }
    .corner { animation: cornerSlide 11s ease-out infinite; }

    @keyframes nameIn {
      0%, 4% { opacity: 0; transform: translateY(8px); }
      14%, 90% { opacity: 1; transform: translateY(0); }
      100% { opacity: 0; transform: translateY(0); }
    }
    @keyframes underlineDraw {
      0%, 14% { transform: scaleX(0); }
      24%, 88% { transform: scaleX(1); }
      100% { transform: scaleX(1); }
    }
    @keyframes fadeUp {
      0%, 22% { opacity: 0; transform: translateY(6px); }
      32%, 90% { opacity: 1; transform: translateY(0); }
      100% { opacity: 0; transform: translateY(0); }
    }
    @keyframes cornerSlide {
      0%, 8% { opacity: 0; transform: translateX(-8px); }
      18%, 90% { opacity: 1; transform: translateX(0); }
      100% { opacity: 0; transform: translateX(0); }
    }
  </style>
  <defs>
    <linearGradient id="hdr-bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0.85"/>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#hdr-bg)" rx="14" ry="14"/>

  <!-- Corner decorations: outer <g> = position, inner <g> = animation -->
  <g class="corner" opacity="0.6">
    <rect x="40" y="42" width="22" height="2" fill="#ffffff" />
    <rect x="40" y="42" width="2" height="22" fill="#ffffff" />
  </g>
  <g transform="translate(800 0) scale(-1 1)">
    <g class="corner" opacity="0.6">
      <rect x="40" y="42" width="22" height="2" fill="#ffffff" />
      <rect x="40" y="42" width="2" height="22" fill="#ffffff" />
    </g>
  </g>

  <!-- Name -->
  <text class="name" x="400" y="138" text-anchor="middle" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="56" font-weight="700" letter-spacing="-1.5">Swapy</text>

  <!-- Accent underline -->
  <rect class="underline" x="330" y="164" width="140" height="2" fill="#ffffff" rx="1"/>

  <!-- Meta line -->
  <text class="meta" x="400" y="200" text-anchor="middle" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="13" letter-spacing="2">SOFTWARE ENGINEER</text>
</svg>

![Uploadin<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">
  <style>
    .heading { animation: slidein 11s ease-out infinite; }
    .bio { animation: fade 11s ease-in-out infinite; }
    .pill { animation: pillpop 11s ease-out infinite; transform-box: fill-box; transform-origin: center; }
    .p0 { animation-delay: 0.4s }
    .accentbar { animation: bar 11s ease-out infinite; transform-origin: top left; }

    @keyframes slidein {
      0% { opacity: 0; transform: translateX(-12px) }
      8% { opacity: 1; transform: translateX(0) }
      90% { opacity: 1; transform: translateX(0) }
      100% { opacity: 0; transform: translateX(0) }
    }
    @keyframes fade {
      0%, 8% { opacity: 0 }
      18% { opacity: 1 }
      90% { opacity: 1 }
      100% { opacity: 0 }
    }
    @keyframes pillpop {
      0%, 14% { opacity: 0; transform: scale(0.85) }
      22% { opacity: 1; transform: scale(1) }
      90% { opacity: 1; transform: scale(1) }
      100% { opacity: 0; transform: scale(1) }
    }
    @keyframes bar {
      0% { transform: scaleY(0) }
      10% { transform: scaleY(1) }
      90% { transform: scaleY(1) }
      100% { transform: scaleY(1) }
    }
  </style>
  <defs>
    <linearGradient id="card-grad" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0.85"/>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#card-grad)" rx="14" ry="14"/>
  <rect x="32" y="32" width="3" height="256" fill="#ffffff" rx="1.5" class="accentbar"/>
  <text class="heading" x="56" y="108" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="32" font-weight="700">Hi, I&apos;m Swapy.</text>
  <text class="bio" x="56" y="158" fill="#a5a5b3" font-family='"Inter", system-ui, sans-serif' font-size="15" font-weight="400"><tspan x="56" dy="0">I like designing creative things and building useful apps. Passionate about</tspan><tspan x="56" dy="22">turning ideas into reality. Always learning and improving my skills.</tspan></text>
  <g transform="translate(56 218.935)">
        <g class="pill p0">
          <rect width="134" height="20.130000000000003" rx="10.065000000000001" fill="#ffffff" fill-opacity="0.12" stroke="#ffffff" stroke-opacity="0.4"/>
          <text x="67" y="10.065000000000001" fill="#f7f7fb" font-size="11" font-family="ui-monospace, monospace" text-anchor="middle" dominant-baseline="middle">Software Engineer</text>
        </g>
      </g>
</svg>g about.svg…]()

<img width="800" height="200" alt="skills" src="https://github.com/user-attachments/assets/8e896f31-7700-4ad5-9405-40dcb9217813" /><svg xmlns="http://www.w3.org/2000/svg" width="800" height="200" viewBox="0 0 800 200">
  <style>
    svg { font-family: "Inter", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, sans-serif; }
    @keyframes chip0 { 0%,0% { opacity: 0; transform: translateY(6px) } 2%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip1 { 0%,3% { opacity: 0; transform: translateY(6px) } 5%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip2 { 0%,5% { opacity: 0; transform: translateY(6px) } 7%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip3 { 0%,8% { opacity: 0; transform: translateY(6px) } 10%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip4 { 0%,10% { opacity: 0; transform: translateY(6px) } 12%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip5 { 0%,13% { opacity: 0; transform: translateY(6px) } 15%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    @keyframes chip6 { 0%,15% { opacity: 0; transform: translateY(6px) } 17%,92% { opacity: 1; transform: translateY(0) } 97%,100% { opacity: 0 } }
    .chip0 { animation: chip0 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip1 { animation: chip1 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip2 { animation: chip2 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip3 { animation: chip3 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip4 { animation: chip4 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip5 { animation: chip5 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
    .chip6 { animation: chip6 11s ease-out infinite; transform-origin: center; transform-box: fill-box; }
  </style>
  <rect width="100%" height="100%" fill="#0d1117" rx="14" ry="14"/>

  <!-- Accent bar -->
  <rect x="56" y="74" width="56" height="3" rx="1.5" fill="#ffffff"/>

  <!-- Heading -->
  <text x="56" y="56" fill="#f7f7fb" font-size="30" font-weight="700" letter-spacing="-0.02em">Stack.</text>

  <!-- Sub-line -->
  <text x="56" y="104" fill="#a5a5b3" font-size="13" font-weight="500" letter-spacing="0.02em">7 tools I reach for daily.</text>

  <!-- Pill rows -->
  <g class="chip0">
        <rect x="141" y="134" width="70.2" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="176.1" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">REACT</text>
      </g>
  <g class="chip1">
        <rect x="221.2" y="134" width="79" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="260.7" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">DESIGN</text>
      </g>
  <g class="chip2">
        <rect x="310.2" y="134" width="44.8" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="332.59999999999997" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">UI</text>
      </g>
  <g class="chip3">
        <rect x="365" y="134" width="44.8" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="387.4" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">UX</text>
      </g>
  <g class="chip4">
        <rect x="419.79999999999995" y="134" width="95.6" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="467.6" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">FRONTEND</text>
      </g>
  <g class="chip5">
        <rect x="525.4" y="134" width="44.8" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="547.8" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">AI</text>
      </g>
  <g class="chip6">
        <rect x="580.1999999999999" y="134" width="79" height="28" rx="14" fill="#0d1117" stroke="#a5a5b3" stroke-width="1" stroke-opacity="0.55"/>
        <text x="619.6999999999999" y="148" fill="#f7f7fb" font-family="ui-monospace, monospace" font-size="13" letter-spacing="0.8" text-anchor="middle" dominant-baseline="middle">PYTHON</text>
      </g>
</svg>

<img width="800" height="320" alt="gh-stats" src="https://github.com/user-attachments/assets/bfccaddc-e454-4594-8698-e0a7c7d81e82" /><svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">
  <style>
    .heading { animation: slidein 11s ease-out infinite; }
    .underline { animation: bar 11s ease-out infinite; transform-origin: left center; }
    .meta { animation: fade 11s ease-in-out infinite; }
    .corner { animation: cornerSlide 11s ease-out infinite; }
    .stat { animation: fadeUp 11s ease-out infinite; }
    .s0 { animation-delay: 0.3s }
    .s1 { animation-delay: 0.4s }
    .s2 { animation-delay: 0.5s }
    .s3 { animation-delay: 0.6000000000000001s }
    .lang-bar { animation: bar 11s ease-out infinite; transform-origin: left center; }

    @keyframes slidein {
      0% { opacity: 0; transform: translateX(-12px) }
      8% { opacity: 1; transform: translateX(0) }
      90% { opacity: 1; transform: translateX(0) }
      100% { opacity: 0; transform: translateX(0) }
    }
    @keyframes bar {
      0%, 14% { transform: scaleX(0) }
      24%, 88% { transform: scaleX(1) }
      100% { transform: scaleX(1) }
    }
    @keyframes fade {
      0%, 22% { opacity: 0 }
      32%, 90% { opacity: 1 }
      100% { opacity: 0 }
    }
    @keyframes fadeUp {
      0%, 22% { opacity: 0; transform: translateY(8px) }
      36%, 90% { opacity: 1; transform: translateY(0) }
      100% { opacity: 0; transform: translateY(0) }
    }
    @keyframes cornerSlide {
      0%, 8% { opacity: 0; transform: translateX(-8px) }
      18%, 90% { opacity: 0.6; transform: translateX(0) }
      100% { opacity: 0; transform: translateX(0) }
    }
  </style>
  <defs>
    <linearGradient id="sleek-stats-bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0.85"/>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#sleek-stats-bg)" rx="14" ry="14"/>

  <!-- corner decorations (mirrors sleek-header) -->
  <g class="corner" opacity="0.6">
    <rect x="40" y="42" width="22" height="2" fill="#ffffff"/>
    <rect x="40" y="42" width="2" height="22" fill="#ffffff"/>
  </g>
  <g transform="translate(800 0) scale(-1 1)">
    <g class="corner" opacity="0.6">
      <rect x="40" y="42" width="22" height="2" fill="#ffffff"/>
      <rect x="40" y="42" width="2" height="22" fill="#ffffff"/>
    </g>
  </g>

  <!-- heading + accent underline -->
  <text class="heading" x="48" y="84" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="36" font-weight="700" letter-spacing="-1.2">Activity.</text>
  <rect class="underline" x="48" y="96" width="181" height="2" fill="#ffffff" rx="1"/>

  <!-- meta line -->
  <text class="meta" x="48" y="120" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="11" letter-spacing="2">@SWAPY-Y   ·   10 CONTRIBUTIONS   ·   GRAPHQL</text>

  <!-- stat blocks -->
  <g transform="translate(48 156)">
      <g class="stat s0">
        <text x="0" y="0" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="2">REPOS</text>
        <text x="0" y="38" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="34" font-weight="700" letter-spacing="-1">2</text>
        <text x="0" y="60" fill="#a5a5b3" font-family='"Inter", system-ui, sans-serif' font-size="11" font-weight="400">2 indexed</text>
      </g>
    </g>
  <g transform="translate(230 156)">
      <g class="stat s1">
        <text x="0" y="0" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="2">COMMITS</text>
        <text x="0" y="38" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="34" font-weight="700" letter-spacing="-1">7</text>
        <text x="0" y="60" fill="#a5a5b3" font-family='"Inter", system-ui, sans-serif' font-size="11" font-weight="400">this year</text>
      </g>
    </g>
  <g transform="translate(412 156)">
      <g class="stat s2">
        <text x="0" y="0" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="2">PRS</text>
        <text x="0" y="38" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="34" font-weight="700" letter-spacing="-1">0</text>
        <text x="0" y="60" fill="#a5a5b3" font-family='"Inter", system-ui, sans-serif' font-size="11" font-weight="400">0 this year</text>
      </g>
    </g>
  <g transform="translate(594 156)">
      <g class="stat s3">
        <text x="0" y="0" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="2">REVIEWS</text>
        <text x="0" y="38" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="34" font-weight="700" letter-spacing="-1">0</text>
        <text x="0" y="60" fill="#a5a5b3" font-family='"Inter", system-ui, sans-serif' font-size="11" font-weight="400">this year</text>
      </g>
    </g>

  <!-- language strip -->
  <rect x="48" y="254" width="704" height="6" rx="3" fill="#a5a5b3" fill-opacity="0.2"/>
  <g class="lang-bar"><rect x="48" y="254" width="437.88800000000003" height="6" rx="3" fill="#44a51c"/>
  <rect x="485.88800000000003" y="254" width="78.14399999999999" height="6" rx="3" fill="#f1e05a"/>
  <rect x="564.032" y="254" width="59.136" height="6" rx="3" fill="#000080"/>
  <rect x="623.168" y="254" width="56.32" height="6" rx="3" fill="#89e051"/>
  <rect x="679.488" y="254" width="72.51199999999994" height="6" rx="3" fill="#663399"/></g>
  <g>
        <rect x="48" y="279" width="8" height="8" rx="2" fill="#44a51c"/>
        <text x="64" y="286" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="1.4">QML  62%</text>
      </g>
  <g>
        <rect x="224" y="279" width="8" height="8" rx="2" fill="#f1e05a"/>
        <text x="240" y="286" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="1.4">JAVASCRIPT  11%</text>
      </g>
  <g>
        <rect x="400" y="279" width="8" height="8" rx="2" fill="#000080"/>
        <text x="416" y="286" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="1.4">LUA  8%</text>
      </g>
  <g>
        <rect x="576" y="279" width="8" height="8" rx="2" fill="#89e051"/>
        <text x="592" y="286" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="10" letter-spacing="1.4">SHELL  8%</text>
      </g>
</svg>

<img width="800" height="160" alt="footer" src="https://github.com/user-attachments/assets/c0c94eb9-3aca-485e-aa24-ada871e13120" /><svg xmlns="http://www.w3.org/2000/svg" width="800" height="160" viewBox="0 0 800 160">
  <style>
    
    .signoff { animation: signoffIn 11s ease-in-out infinite; }
    .soc { animation: socfade 11s ease-in-out infinite; }
    .sf0 { animation-delay: 0.60s }

    @keyframes signoffIn {
      0%, 8% { opacity: 0; transform: translateY(4px); }
      18%, 90% { opacity: 1; transform: translateY(0); }
      100% { opacity: 0; transform: translateY(0); }
    }
    @keyframes socfade {
      0%, 22% { opacity: 0; }
      32%, 90% { opacity: 1; }
      100% { opacity: 0; }
    }
  
    .heart { animation: heartbeat 11s ease-in-out infinite; transform-box: fill-box; transform-origin: center; }
    .wave-front { animation: drift-front 11s linear infinite; }
    .wave-back { animation: drift-back 11s linear infinite; }

    @keyframes heartbeat {
      0%, 40% { transform: scale(1); }
      45% { transform: scale(1.18); }
      50% { transform: scale(1); }
      55% { transform: scale(1.12); }
      60%, 100% { transform: scale(1); }
    }
    @keyframes drift-front {
      from { transform: translateX(0); }
      to { transform: translateX(-160px); }
    }
    @keyframes drift-back {
      from { transform: translateX(0); }
      to { transform: translateX(256px); }
    }
  </style>
  <defs>
    <linearGradient id="wave-fade" x1="0" y1="0" x2="1" y2="0" gradientUnits="objectBoundingBox">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="15%" stop-color="#ffffff" stop-opacity="0.45"/>
      <stop offset="85%" stop-color="#ffffff" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="wave-fade-back" x1="0" y1="0" x2="1" y2="0" gradientUnits="objectBoundingBox">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="15%" stop-color="#ffffff" stop-opacity="0.16"/>
      <stop offset="85%" stop-color="#ffffff" stop-opacity="0.16"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <!-- Mask to fade the wave near the left/right edges so it tucks into the rounded corners. -->
    <linearGradient id="edge-mask" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="white" stop-opacity="0"/>
      <stop offset="10%" stop-color="white" stop-opacity="1"/>
      <stop offset="90%" stop-color="white" stop-opacity="1"/>
      <stop offset="100%" stop-color="white" stop-opacity="0"/>
    </linearGradient>
    <mask id="edge-fade">
      <rect width="800" height="160" fill="url(#edge-mask)"/>
    </mask>
  </defs>

  <rect width="100%" height="100%" fill="#0d1117" rx="14" ry="14"/>

  <!-- Sine waves: outer <g> handles edge mask + animation translate -->
  <g mask="url(#edge-fade)">
    <g class="wave-back">
      <path d="M -320 66.00 L -312 66.27 L -304 67.07 L -296 68.36 L -288 70.10 L -280 72.22 L -272 74.64 L -264 77.27 L -256 80.00 L -248 82.73 L -240 85.36 L -232 87.78 L -224 89.90 L -216 91.64 L -208 92.93 L -200 93.73 L -192 94.00 L -184 93.73 L -176 92.93 L -168 91.64 L -160 89.90 L -152 87.78 L -144 85.36 L -136 82.73 L -128 80.00 L -120 77.27 L -112 74.64 L -104 72.22 L -96 70.10 L -88 68.36 L -80 67.07 L -72 66.27 L -64 66.00 L -56 66.27 L -48 67.07 L -40 68.36 L -32 70.10 L -24 72.22 L -16 74.64 L -8 77.27 L 0 80.00 L 8 82.73 L 16 85.36 L 24 87.78 L 32 89.90 L 40 91.64 L 48 92.93 L 56 93.73 L 64 94.00 L 72 93.73 L 80 92.93 L 88 91.64 L 96 89.90 L 104 87.78 L 112 85.36 L 120 82.73 L 128 80.00 L 136 77.27 L 144 74.64 L 152 72.22 L 160 70.10 L 168 68.36 L 176 67.07 L 184 66.27 L 192 66.00 L 200 66.27 L 208 67.07 L 216 68.36 L 224 70.10 L 232 72.22 L 240 74.64 L 248 77.27 L 256 80.00 L 264 82.73 L 272 85.36 L 280 87.78 L 288 89.90 L 296 91.64 L 304 92.93 L 312 93.73 L 320 94.00 L 328 93.73 L 336 92.93 L 344 91.64 L 352 89.90 L 360 87.78 L 368 85.36 L 376 82.73 L 384 80.00 L 392 77.27 L 400 74.64 L 408 72.22 L 416 70.10 L 424 68.36 L 432 67.07 L 440 66.27 L 448 66.00 L 456 66.27 L 464 67.07 L 472 68.36 L 480 70.10 L 488 72.22 L 496 74.64 L 504 77.27 L 512 80.00 L 520 82.73 L 528 85.36 L 536 87.78 L 544 89.90 L 552 91.64 L 560 92.93 L 568 93.73 L 576 94.00 L 584 93.73 L 592 92.93 L 600 91.64 L 608 89.90 L 616 87.78 L 624 85.36 L 632 82.73 L 640 80.00 L 648 77.27 L 656 74.64 L 664 72.22 L 672 70.10 L 680 68.36 L 688 67.07 L 696 66.27 L 704 66.00 L 712 66.27 L 720 67.07 L 728 68.36 L 736 70.10 L 744 72.22 L 752 74.64 L 760 77.27 L 768 80.00 L 776 82.73 L 784 85.36 L 792 87.78 L 800 89.90 L 808 91.64 L 816 92.93 L 824 93.73 L 832 94.00 L 840 93.73 L 848 92.93 L 856 91.64 L 864 89.90 L 872 87.78 L 880 85.36 L 888 82.73 L 896 80.00 L 904 77.27 L 912 74.64 L 920 72.22 L 928 70.10 L 936 68.36 L 944 67.07 L 952 66.27 L 960 66.00 L 968 66.27 L 976 67.07 L 984 68.36 L 992 70.10 L 1000 72.22 L 1008 74.64 L 1016 77.27 L 1024 80.00 L 1032 82.73 L 1040 85.36 L 1048 87.78 L 1056 89.90 L 1064 91.64 L 1072 92.93 L 1080 93.73 L 1088 94.00 L 1096 93.73 L 1104 92.93 L 1112 91.64 L 1120 89.90" stroke="url(#wave-fade-back)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
    </g>
    <g class="wave-front">
      <path d="M -320 80.00 L -314 82.10 L -308 84.09 L -302 85.85 L -296 87.28 L -290 88.31 L -284 88.89 L -278 88.97 L -272 88.56 L -266 87.67 L -260 86.36 L -254 84.70 L -248 82.78 L -242 80.71 L -236 78.59 L -230 76.56 L -224 74.71 L -218 73.16 L -212 71.98 L -206 71.25 L -200 71.00 L -194 71.25 L -188 71.98 L -182 73.16 L -176 74.71 L -170 76.56 L -164 78.59 L -158 80.71 L -152 82.78 L -146 84.70 L -140 86.36 L -134 87.67 L -128 88.56 L -122 88.97 L -116 88.89 L -110 88.31 L -104 87.28 L -98 85.85 L -92 84.09 L -86 82.10 L -80 80.00 L -74 77.90 L -68 75.91 L -62 74.15 L -56 72.72 L -50 71.69 L -44 71.11 L -38 71.03 L -32 71.44 L -26 72.33 L -20 73.64 L -14 75.30 L -8 77.22 L -2 79.29 L 4 81.41 L 10 83.44 L 16 85.29 L 22 86.84 L 28 88.02 L 34 88.75 L 40 89.00 L 46 88.75 L 52 88.02 L 58 86.84 L 64 85.29 L 70 83.44 L 76 81.41 L 82 79.29 L 88 77.22 L 94 75.30 L 100 73.64 L 106 72.33 L 112 71.44 L 118 71.03 L 124 71.11 L 130 71.69 L 136 72.72 L 142 74.15 L 148 75.91 L 154 77.90 L 160 80.00 L 166 82.10 L 172 84.09 L 178 85.85 L 184 87.28 L 190 88.31 L 196 88.89 L 202 88.97 L 208 88.56 L 214 87.67 L 220 86.36 L 226 84.70 L 232 82.78 L 238 80.71 L 244 78.59 L 250 76.56 L 256 74.71 L 262 73.16 L 268 71.98 L 274 71.25 L 280 71.00 L 286 71.25 L 292 71.98 L 298 73.16 L 304 74.71 L 310 76.56 L 316 78.59 L 322 80.71 L 328 82.78 L 334 84.70 L 340 86.36 L 346 87.67 L 352 88.56 L 358 88.97 L 364 88.89 L 370 88.31 L 376 87.28 L 382 85.85 L 388 84.09 L 394 82.10 L 400 80.00 L 406 77.90 L 412 75.91 L 418 74.15 L 424 72.72 L 430 71.69 L 436 71.11 L 442 71.03 L 448 71.44 L 454 72.33 L 460 73.64 L 466 75.30 L 472 77.22 L 478 79.29 L 484 81.41 L 490 83.44 L 496 85.29 L 502 86.84 L 508 88.02 L 514 88.75 L 520 89.00 L 526 88.75 L 532 88.02 L 538 86.84 L 544 85.29 L 550 83.44 L 556 81.41 L 562 79.29 L 568 77.22 L 574 75.30 L 580 73.64 L 586 72.33 L 592 71.44 L 598 71.03 L 604 71.11 L 610 71.69 L 616 72.72 L 622 74.15 L 628 75.91 L 634 77.90 L 640 80.00 L 646 82.10 L 652 84.09 L 658 85.85 L 664 87.28 L 670 88.31 L 676 88.89 L 682 88.97 L 688 88.56 L 694 87.67 L 700 86.36 L 706 84.70 L 712 82.78 L 718 80.71 L 724 78.59 L 730 76.56 L 736 74.71 L 742 73.16 L 748 71.98 L 754 71.25 L 760 71.00 L 766 71.25 L 772 71.98 L 778 73.16 L 784 74.71 L 790 76.56 L 796 78.59 L 802 80.71 L 808 82.78 L 814 84.70 L 820 86.36 L 826 87.67 L 832 88.56 L 838 88.97 L 844 88.89 L 850 88.31 L 856 87.28 L 862 85.85 L 868 84.09 L 874 82.10 L 880 80.00 L 886 77.90 L 892 75.91 L 898 74.15 L 904 72.72 L 910 71.69 L 916 71.11 L 922 71.03 L 928 71.44 L 934 72.33 L 940 73.64 L 946 75.30 L 952 77.22 L 958 79.29 L 964 81.41 L 970 83.44 L 976 85.29 L 982 86.84 L 988 88.02 L 994 88.75 L 1000 89.00 L 1006 88.75 L 1012 88.02 L 1018 86.84 L 1024 85.29 L 1030 83.44 L 1036 81.41 L 1042 79.29 L 1048 77.22 L 1054 75.30 L 1060 73.64 L 1066 72.33 L 1072 71.44 L 1078 71.03 L 1084 71.11 L 1090 71.69 L 1096 72.72 L 1102 74.15 L 1108 75.91 L 1114 77.90 L 1120 80.00" stroke="url(#wave-fade)" stroke-width="1.75" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
    </g>
  </g>

  <!-- Sign-off line -->
  <text class="signoff" x="400" y="70" text-anchor="middle" fill="#f7f7fb" font-family='"Inter", system-ui, sans-serif' font-size="14" font-weight="500">made with <tspan class="heart" fill="#ffffff">♥</tspan> by Swapy - UI/UX, Frontend, LLMs, Software Design</text>

  <g transform="translate(325 94)">
        <g class="soc sf0">
          <g transform="translate(0 -7)"><svg viewBox="0 0 24 24" width="14" height="14" fill="none" stroke="#a5a5b3" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg></g>
          <text x="20" y="0" fill="#a5a5b3" font-family="ui-monospace, monospace" font-size="12" dominant-baseline="middle">github.com/Swapy-y</text>
        </g>
      </g>

  <!-- ryme.md attribution: low-opacity mono credit in the bottom-right. -->
  <text x="782" y="148" fill="#a5a5b3" fill-opacity="0.4" font-family="ui-monospace, monospace" font-size="10" text-anchor="end">made with ryme.md</text>
</svg>
