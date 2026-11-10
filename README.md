<img width="800" height="320" alt="about" src="https://github.com/user-attachments/assets/10e0b4ff-1a0e-4b2b-826a-bba64f7a7155" /><img width="800" height="300" alt="header" src="https://github.com/user-attachments/assets/f71b3f15-a7a8-446e-94c7-5946a06ebde1" />
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
<img width="800" height="320" alt="about" src="https://github.com/user-attachments/assets/33ea1591-7f38-479e-bea0-4da49067365b" />
<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">
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
</svg>

![Uploading a<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">
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
</svg>bout.svg…]()
