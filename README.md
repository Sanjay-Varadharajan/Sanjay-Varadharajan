<div align="center">

<!-- ████████████████████████████████████████████████████████████ -->
<!--                    HERO COMMAND CENTER                       -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="320" viewBox="0 0 900 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#030d2a;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#020818;stop-opacity:1" />
    </linearGradient>
    <!-- Cyan glow -->
    <filter id="cyanGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Magenta glow -->
    <filter id="magentaGlow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Strong glow -->
    <filter id="strongGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Scanline pattern -->
    <pattern id="scanlines" x="0" y="0" width="900" height="4" patternUnits="userSpaceOnUse">
      <rect width="900" height="2" fill="rgba(0,255,255,0.03)"/>
      <rect y="2" width="900" height="2" fill="transparent"/>
    </pattern>
    <!-- Grid pattern -->
    <pattern id="grid" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(0,200,255,0.06)" stroke-width="0.5"/>
    </pattern>
    <!-- Neon cyan gradient for text -->
    <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5ff"/>
      <stop offset="50%" style="stop-color:#ffffff"/>
      <stop offset="100%" style="stop-color:#00f5ff"/>
    </linearGradient>
    <!-- Magenta gradient -->
    <linearGradient id="magentaGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff00c8"/>
      <stop offset="100%" style="stop-color:#bf00ff"/>
    </linearGradient>
    <!-- Building gradient -->
    <linearGradient id="buildGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#1a3a5c"/>
      <stop offset="100%" style="stop-color:#050d1a"/>
    </linearGradient>
    <!-- Ground glow -->
    <radialGradient id="groundGlow" cx="50%" cy="100%" r="60%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#020818;stop-opacity:0"/>
    </radialGradient>
    <!-- Cat body gradient -->
    <linearGradient id="catGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e"/>
      <stop offset="100%" style="stop-color:#0a0a15"/>
    </linearGradient>
    <!-- Hologram gradient -->
    <linearGradient id="holoGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </linearGradient>

  </defs>

  <!-- Background -->
  <rect width="900" height="320" fill="url(#bgGrad)"/>
  <rect width="900" height="320" fill="url(#grid)"/>
  <rect width="900" height="320" fill="url(#scanlines)"/>

  <!-- Ground neon glow -->
  <rect width="900" height="320" fill="url(#groundGlow)"/>

  <!-- ═══════════════ CITY SKYLINE ═══════════════ -->

  <!-- Far buildings - layer 1 (darkest) -->
  <rect x="0" y="220" width="25" height="100" fill="#061428" opacity="0.6"/>
  <rect x="20" y="200" width="18" height="120" fill="#061428" opacity="0.6"/>
  <rect x="33" y="210" width="30" height="110" fill="#071830" opacity="0.7"/>
  <rect x="58" y="195" width="22" height="125" fill="#061428" opacity="0.6"/>
  <rect x="75" y="215" width="35" height="105" fill="#071830" opacity="0.7"/>
  <rect x="105" y="185" width="28" height="135" fill="#061428" opacity="0.6"/>
  <rect x="128" y="205" width="40" height="115" fill="#071830" opacity="0.7"/>
  <rect x="163" y="190" width="20" height="130" fill="#061428" opacity="0.6"/>
  <rect x="178" y="178" width="35" height="142" fill="#071830" opacity="0.7"/>
  <rect x="208" y="200" width="50" height="120" fill="#061428" opacity="0.6"/>
  <rect x="253" y="210" width="22" height="110" fill="#071830" opacity="0.7"/>
  <rect x="270" y="188" width="38" height="132" fill="#061428" opacity="0.6"/>
  <rect x="303" y="195" width="28" height="125" fill="#071830" opacity="0.7"/>
  <rect x="326" y="175" width="45" height="145" fill="#061428" opacity="0.6"/>
  <rect x="366" y="205" width="30" height="115" fill="#071830" opacity="0.7"/>
  <rect x="391" y="185" width="55" height="135" fill="#061428" opacity="0.6"/>
  <rect x="441" y="200" width="25" height="120" fill="#071830" opacity="0.7"/>
  <rect x="461" y="178" width="42" height="142" fill="#061428" opacity="0.6"/>
  <rect x="498" y="195" width="38" height="125" fill="#071830" opacity="0.7"/>
  <rect x="531" y="180" width="30" height="140" fill="#061428" opacity="0.6"/>
  <rect x="556" y="200" width="55" height="120" fill="#071830" opacity="0.7"/>
  <rect x="606" y="185" width="25" height="135" fill="#061428" opacity="0.6"/>
  <rect x="626" y="195" width="40" height="125" fill="#071830" opacity="0.7"/>
  <rect x="661" y="175" width="35" height="145" fill="#061428" opacity="0.6"/>
  <rect x="691" y="200" width="50" height="120" fill="#071830" opacity="0.7"/>
  <rect x="736" y="188" width="28" height="132" fill="#061428" opacity="0.6"/>
  <rect x="759" y="205" width="45" height="115" fill="#071830" opacity="0.7"/>
  <rect x="799" y="180" width="35" height="140" fill="#061428" opacity="0.6"/>
  <rect x="829" y="195" width="55" height="125" fill="#071830" opacity="0.7"/>
  <rect x="879" y="210" width="21" height="110" fill="#061428" opacity="0.6"/>

  <!-- Mid buildings - layer 2 -->
  <rect x="10" y="215" width="20" height="105" fill="#0a1e3d"/>
  <rect x="45" y="190" width="28" height="130" fill="#0c2040"/>
  <rect x="88" y="205" width="35" height="115" fill="#0a1e3d"/>
  <rect x="140" y="180" width="22" height="140" fill="#0c2040"/>
  <!-- Tall tower left -->
  <rect x="165" y="155" width="18" height="165" fill="#0a1a38"/>
  <rect x="173" y="148" width="4" height="10" fill="#00f5ff" opacity="0.8"/>

  <rect x="220" y="195" width="40" height="125" fill="#0a1e3d"/>
  <rect x="280" y="170" width="30" height="150" fill="#0c2040"/>
  <!-- Tall tower center-left -->
  <rect x="320" y="145" width="22" height="175" fill="#0a1a38"/>
  <rect x="330" y="138" width="4" height="10" fill="#ff00c8" opacity="0.9"/>

  <rect x="400" y="185" width="45" height="135" fill="#0a1e3d"/>
  <!-- Supertall center -->
  <rect x="445" y="120" width="28" height="200" fill="#0c1e40"/>
  <rect x="457" y="112" width="5" height="12" fill="#00f5ff"/>
  <rect x="455" y="108" width="9" height="5" fill="#00f5ff" opacity="0.6"/>

  <rect x="510" y="175" width="35" height="145" fill="#0a1e3d"/>
  <rect x="570" y="190" width="50" height="130" fill="#0c2040"/>
  <!-- Tall tower right -->
  <rect x="630" y="150" width="20" height="170" fill="#0a1a38"/>
  <rect x="639" y="142" width="4" height="10" fill="#00f5ff" opacity="0.8"/>

  <rect x="670" y="185" width="42" height="135" fill="#0a1e3d"/>
  <rect x="730" y="170" width="30" height="150" fill="#0c2040"/>
  <!-- Supertall right -->
  <rect x="775" y="130" width="25" height="190" fill="#0c1e40"/>
  <rect x="785" y="122" width="5" height="12" fill="#ff00c8"/>

  <rect x="820" y="195" width="50" height="125" fill="#0a1e3d"/>
  <rect x="865" y="178" width="35" height="142" fill="#0c2040"/>

  <!-- Building windows - animated blinking lights -->
  <!-- Left cluster -->
  <rect x="170" y="165" width="3" height="3" fill="#00f5ff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.1;0.9" dur="2.3s" repeatCount="indefinite"/></rect>
  <rect x="176" y="172" width="3" height="3" fill="#ffd700" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="1.7s" repeatCount="indefinite"/></rect>
  <rect x="170" y="180" width="3" height="3" fill="#00f5ff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="3.1s" repeatCount="indefinite"/></rect>
  <rect x="50" y="200" width="3" height="3" fill="#ffd700" opacity="0.8"><animate attributeName="opacity" values="0.8;0;0.8" dur="2.8s" repeatCount="indefinite"/></rect>
  <rect x="56" y="208" width="3" height="3" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0;0.6" dur="1.9s" repeatCount="indefinite"/></rect>
  <rect x="50" y="216" width="3" height="3" fill="#ff00c8" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.4s" repeatCount="indefinite"/></rect>
  <!-- Center cluster -->
  <rect x="330" y="158" width="3" height="3" fill="#ff00c8" opacity="0.9"><animate attributeName="opacity" values="0.9;0.2;0.9" dur="2.1s" repeatCount="indefinite"/></rect>
  <rect x="324" y="166" width="3" height="3" fill="#00f5ff" opacity="0.8"><animate attributeName="opacity" values="0.8;0;0.8" dur="3.3s" repeatCount="indefinite"/></rect>
  <rect x="330" y="174" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0.3;0.7" dur="1.5s" repeatCount="indefinite"/></rect>
  <rect x="450" y="132" width="3" height="3" fill="#00f5ff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.1;0.9" dur="2.6s" repeatCount="indefinite"/></rect>
  <rect x="456" y="140" width="3" height="3" fill="#ff00c8" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="1.8s" repeatCount="indefinite"/></rect>
  <rect x="450" y="150" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0;0.7" dur="2.9s" repeatCount="indefinite"/></rect>
  <!-- Right cluster -->
  <rect x="635" y="162" width="3" height="3" fill="#00f5ff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.1;0.9" dur="2.2s" repeatCount="indefinite"/></rect>
  <rect x="641" y="170" width="3" height="3" fill="#ff00c8" opacity="0.8"><animate attributeName="opacity" values="0.8;0.3;0.8" dur="3.0s" repeatCount="indefinite"/></rect>
  <rect x="635" y="178" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0;0.7" dur="1.6s" repeatCount="indefinite"/></rect>
  <rect x="780" y="142" width="3" height="3" fill="#ff00c8" opacity="0.9"><animate attributeName="opacity" values="0.9;0.2;0.9" dur="2.7s" repeatCount="indefinite"/></rect>
  <rect x="786" y="150" width="3" height="3" fill="#00f5ff" opacity="0.8"><animate attributeName="opacity" values="0.8;0;0.8" dur="1.4s" repeatCount="indefinite"/></rect>
  <rect x="780" y="160" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="3.5s" repeatCount="indefinite"/></rect>

  <!-- More scattered windows -->
  <rect x="93" y="215" width="3" height="3" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0;0.6" dur="2.0s" repeatCount="indefinite"/></rect>
  <rect x="100" y="222" width="3" height="3" fill="#ff00c8" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="1.3s" repeatCount="indefinite"/></rect>
  <rect x="226" y="205" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0;0.7" dur="2.5s" repeatCount="indefinite"/></rect>
  <rect x="233" y="213" width="3" height="3" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.2;0.6" dur="1.6s" repeatCount="indefinite"/></rect>
  <rect x="406" y="195" width="3" height="3" fill="#ff00c8" opacity="0.7"><animate attributeName="opacity" values="0.7;0;0.7" dur="2.3s" repeatCount="indefinite"/></rect>
  <rect x="413" y="203" width="3" height="3" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="3.2s" repeatCount="indefinite"/></rect>
  <rect x="515" y="185" width="3" height="3" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="1.9s" repeatCount="indefinite"/></rect>
  <rect x="522" y="193" width="3" height="3" fill="#ff00c8" opacity="0.6"><animate attributeName="opacity" values="0.6;0;0.6" dur="2.8s" repeatCount="indefinite"/></rect>
  <rect x="675" y="195" width="3" height="3" fill="#00f5ff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.1s" repeatCount="indefinite"/></rect>
  <rect x="682" y="203" width="3" height="3" fill="#ffd700" opacity="0.6"><animate attributeName="opacity" values="0.6;0;0.6" dur="1.7s" repeatCount="indefinite"/></rect>
  <rect x="825" y="205" width="3" height="3" fill="#ff00c8" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="3.1s" repeatCount="indefinite"/></rect>
  <rect x="832" y="213" width="3" height="3" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0;0.6" dur="2.4s" repeatCount="indefinite"/></rect>

  <!-- Neon sign strips on buildings -->
  <rect x="90" y="205" width="30" height="2" fill="#00f5ff" opacity="0.6" filter="url(#cyanGlow)"><animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/></rect>
  <rect x="285" y="175" width="20" height="2" fill="#ff00c8" opacity="0.8" filter="url(#magentaGlow)"><animate attributeName="opacity" values="0.8;1;0.8" dur="2.5s" repeatCount="indefinite"/></rect>
  <rect x="405" y="188" width="35" height="2" fill="#00f5ff" opacity="0.7" filter="url(#cyanGlow)"><animate attributeName="opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/></rect>
  <rect x="575" y="193" width="45" height="2" fill="#ff00c8" opacity="0.7" filter="url(#magentaGlow)"><animate attributeName="opacity" values="0.7;1;0.7" dur="2.8s" repeatCount="indefinite"/></rect>
  <rect x="675" y="188" width="37" height="2" fill="#00f5ff" opacity="0.6" filter="url(#cyanGlow)"><animate attributeName="opacity" values="0.6;1;0.6" dur="3.5s" repeatCount="indefinite"/></rect>
  <rect x="820" y="198" width="45" height="2" fill="#ffd700" opacity="0.7"><animate attributeName="opacity" values="0.7;1;0.7" dur="2.2s" repeatCount="indefinite"/></rect>

  <!-- Ground line - neon horizon -->
  <line x1="0" y1="290" x2="900" y2="290" stroke="#00f5ff" stroke-width="1.5" opacity="0.4" filter="url(#cyanGlow)"/>
  <line x1="0" y1="292" x2="900" y2="292" stroke="#00f5ff" stroke-width="0.5" opacity="0.2"/>
  <!-- Ground reflection gradient -->
  <rect x="0" y="290" width="900" height="30" fill="url(#holoGrad)" opacity="0.3"/>

  <!-- ═══════════════ FLYING HACKER CATS ═══════════════ -->

  <!-- Cat 1: Main flying hacker cat - moves left to right -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="-80,0; 980,0" dur="18s" repeatCount="indefinite" calcMode="linear"/>
    <!-- Body -->
    <ellipse cx="40" cy="85" rx="14" ry="10" fill="#1a1a2e" stroke="#00f5ff" stroke-width="1"/>
    <!-- Head -->
    <ellipse cx="54" cy="80" rx="11" ry="10" fill="#1a1a2e" stroke="#00f5ff" stroke-width="1"/>
    <!-- Ears -->
    <polygon points="48,72 51,66 55,72" fill="#1a1a2e" stroke="#00f5ff" stroke-width="0.8"/>
    <polygon points="55,72 58,66 61,72" fill="#1a1a2e" stroke="#00f5ff" stroke-width="0.8"/>
    <!-- Goggles -->
    <ellipse cx="50" cy="79" rx="5" ry="4" fill="#ff00c8" opacity="0.3" stroke="#ff00c8" stroke-width="1.2"/>
    <ellipse cx="59" cy="79" rx="5" ry="4" fill="#ff00c8" opacity="0.3" stroke="#ff00c8" stroke-width="1.2"/>
    <line x1="55" y1="79" x2="54" y2="79" stroke="#ff00c8" stroke-width="1"/>
    <!-- Goggle lenses glow -->
    <ellipse cx="50" cy="79" rx="3" ry="2.5" fill="#ff00c8" opacity="0.6" filter="url(#magentaGlow)"><animate attributeName="opacity" values="0.6;1;0.6" dur="1.5s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="59" cy="79" rx="3" ry="2.5" fill="#ff00c8" opacity="0.6" filter="url(#magentaGlow)"><animate attributeName="opacity" values="0.6;1;0.6" dur="1.5s" repeatCount="indefinite"/></ellipse>
    <!-- Nose -->
    <ellipse cx="56" cy="83" rx="1.5" ry="1" fill="#ff00c8"/>
    <!-- Whiskers -->
    <line x1="56" y1="83" x2="45" y2="80" stroke="#00f5ff" stroke-width="0.5" opacity="0.7"/>
    <line x1="56" y1="84" x2="45" y2="85" stroke="#00f5ff" stroke-width="0.5" opacity="0.7"/>
    <line x1="56" y1="83" x2="67" y2="80" stroke="#00f5ff" stroke-width="0.5" opacity="0.7"/>
    <!-- Tail - wagging -->
    <path d="M 30 88 Q 22 82 26 75" fill="none" stroke="#00f5ff" stroke-width="1.5" stroke-linecap="round">
      <animate attributeName="d" values="M 30 88 Q 22 82 26 75; M 30 88 Q 20 88 22 80; M 30 88 Q 22 82 26 75" dur="0.8s" repeatCount="indefinite"/>
    </path>
    <!-- Wings / jetpack -->
    <ellipse cx="38" cy="83" rx="8" ry="4" fill="#00f5ff" opacity="0.2" stroke="#00f5ff" stroke-width="0.8">
      <animate attributeName="ry" values="4;6;4" dur="0.4s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Jet flames -->
    <ellipse cx="35" cy="90" rx="3" ry="5" fill="#ff6600" opacity="0.8">
      <animate attributeName="ry" values="5;8;3;6;5" dur="0.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.8;1;0.6;0.9;0.8" dur="0.3s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="35" cy="90" rx="2" ry="3" fill="#ffd700" opacity="0.9">
      <animate attributeName="ry" values="3;5;2;4;3" dur="0.3s" repeatCount="indefinite"/>
    </ellipse>
  </g>

  <!-- Cat 2: Second cat, slightly higher, delayed -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="-80,-20; 980,-20" dur="25s" repeatCount="indefinite" calcMode="linear" begin="8s"/>
    <!-- Body -->
    <ellipse cx="40" cy="105" rx="12" ry="9" fill="#12122a" stroke="#bf00ff" stroke-width="1"/>
    <!-- Head -->
    <ellipse cx="52" cy="100" rx="10" ry="9" fill="#12122a" stroke="#bf00ff" stroke-width="1"/>
    <!-- Ears -->
    <polygon points="47,93 50,87 53,93" fill="#12122a" stroke="#bf00ff" stroke-width="0.8"/>
    <polygon points="53,93 56,87 59,93" fill="#12122a" stroke="#bf00ff" stroke-width="0.8"/>
    <!-- Goggles -->
    <ellipse cx="48" cy="99" rx="4.5" ry="3.5" fill="#00f5ff" opacity="0.3" stroke="#00f5ff" stroke-width="1.2"/>
    <ellipse cx="57" cy="99" rx="4.5" ry="3.5" fill="#00f5ff" opacity="0.3" stroke="#00f5ff" stroke-width="1.2"/>
    <ellipse cx="48" cy="99" rx="2.5" ry="2" fill="#00f5ff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="2s" repeatCount="indefinite"/></ellipse>
    <ellipse cx="57" cy="99" rx="2.5" ry="2" fill="#00f5ff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="2s" repeatCount="indefinite"/></ellipse>
    <!-- Tail -->
    <path d="M 28 107 Q 20 100 24 93" fill="none" stroke="#bf00ff" stroke-width="1.5" stroke-linecap="round">
      <animate attributeName="d" values="M 28 107 Q 20 100 24 93; M 28 107 Q 18 106 20 98; M 28 107 Q 20 100 24 93" dur="0.9s" repeatCount="indefinite"/>
    </path>
    <!-- Jetpack flame -->
    <ellipse cx="33" cy="110" rx="2.5" ry="4" fill="#ff00c8" opacity="0.8">
      <animate attributeName="ry" values="4;7;3;5;4" dur="0.25s" repeatCount="indefinite"/>
    </ellipse>
  </g>

  <!-- ═══════════════ MAIN TITLE TEXT ═══════════════ -->

  <!-- System prefix -->
  <text x="450" y="38" font-family="'Courier New', monospace" font-size="10" fill="#00f5ff" opacity="0.7" text-anchor="middle" letter-spacing="6">◈ BACKEND COMMAND CENTER ◈</text>

  <!-- Name - giant cyberpunk style -->
  <text x="450" y="78" font-family="'Courier New', monospace" font-size="38" font-weight="bold" fill="url(#cyanGrad)" text-anchor="middle" filter="url(#strongGlow)" letter-spacing="4">SANJAY VARADHARAJAN</text>
  <!-- Name shadow/echo -->
  <text x="453" y="81" font-family="'Courier New', monospace" font-size="38" font-weight="bold" fill="#ff00c8" text-anchor="middle" opacity="0.15" letter-spacing="4">SANJAY VARADHARAJAN</text>

  <!-- Horizontal rule lines -->
  <line x1="60" y1="90" x2="310" y2="90" stroke="url(#cyanGrad)" stroke-width="1" opacity="0.6"/>
  <line x1="590" y1="90" x2="840" y2="90" stroke="url(#cyanGrad)" stroke-width="1" opacity="0.6"/>
  <polygon points="310,90 320,86 320,94" fill="#00f5ff" opacity="0.6"/>
  <polygon points="590,90 580,86 580,94" fill="#00f5ff" opacity="0.6"/>

  <!-- Role -->
  <text x="450" y="112" font-family="'Courier New', monospace" font-size="14" fill="#bf00ff" text-anchor="middle" letter-spacing="8" filter="url(#magentaGlow)">BACKEND  &amp;  SYSTEMS  ENGINEER</text>

  <!-- Animated typing lines -->
  <g>
    <text x="450" y="140" font-family="'Courier New', monospace" font-size="13" fill="#00f5ff" text-anchor="middle" letter-spacing="2">
      <animate attributeName="opacity" values="1;1;1;1;0;0;0;0;0;0;0;0;0;0;0;0" dur="16s" repeatCount="indefinite"/>
      &gt; Building Secure Systems...<tspan fill="#00f5ff" opacity="0.8">█</tspan>
    </text>
    <text x="450" y="140" font-family="'Courier New', monospace" font-size="13" fill="#ff00c8" text-anchor="middle" letter-spacing="2">
      <animate attributeName="opacity" values="0;0;0;0;1;1;1;1;0;0;0;0;0;0;0;0" dur="16s" repeatCount="indefinite"/>
      &gt; Defending APIs...<tspan fill="#ff00c8" opacity="0.8">█</tspan>
    </text>
    <text x="450" y="140" font-family="'Courier New', monospace" font-size="13" fill="#ffd700" text-anchor="middle" letter-spacing="2">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;0;1;1;1;1;0;0;0;0" dur="16s" repeatCount="indefinite"/>
      &gt; Training AI Against Fraud...<tspan fill="#ffd700" opacity="0.8">█</tspan>
    </text>
    <text x="450" y="140" font-family="'Courier New', monospace" font-size="13" fill="#00ff88" text-anchor="middle" letter-spacing="2">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;0;0;0;0;0;1;1;1;1" dur="16s" repeatCount="indefinite"/>
      &gt; Scaling Cloud Infrastructure...<tspan fill="#00ff88" opacity="0.8">█</tspan>
    </text>
  </g>

  <!-- Status bar at bottom -->
  <rect x="20" y="298" width="860" height="16" fill="rgba(0,245,255,0.05)" rx="2" stroke="#00f5ff" stroke-width="0.5" opacity="0.5"/>
  <rect x="22" y="300" width="200" height="12" rx="1" fill="rgba(0,245,255,0.15)">
    <animate attributeName="width" values="200;220;200" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="30" y="310" font-family="'Courier New', monospace" font-size="8" fill="#00f5ff" opacity="0.8">SYS_STATUS: OPERATIONAL</text>
  <text x="360" y="310" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" opacity="0.8" text-anchor="middle">ALL SERVICES ONLINE</text>
  <text x="870" y="310" font-family="'Courier New', monospace" font-size="8" fill="#ff00c8" opacity="0.8" text-anchor="end">v4.2.0-CYBERPUNK</text>
</svg>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                    TECH STACK BADGES                         -->
<!-- ████████████████████████████████████████████████████████████ -->

<br/>

![Java](https://img.shields.io/badge/Java-%23FF6B35.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-%23000000.svg?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-%2300BCD4.svg?style=for-the-badge&logo=fastapi&logoColor=white)

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--              LIVE INFRASTRUCTURE VISUALIZATION               -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="420" viewBox="0 0 900 420" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="infraBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818"/>
      <stop offset="100%" style="stop-color:#030d2a"/>
    </linearGradient>
    <filter id="glow2"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <filter id="glow3"><feGaussianBlur stdDeviation="5" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <pattern id="grid2" x="0" y="0" width="30" height="30" patternUnits="userSpaceOnUse">
      <path d="M 30 0 L 0 0 0 30" fill="none" stroke="rgba(0,200,255,0.04)" stroke-width="0.5"/>
    </pattern>
    <!-- Node gradients -->
    <linearGradient id="nodeGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a2040"/>
      <stop offset="100%" style="stop-color:#051020"/>
    </linearGradient>
    <linearGradient id="nodeGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0a30"/>
      <stop offset="100%" style="stop-color:#0a0520"/>
    </linearGradient>
    <linearGradient id="nodeGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a2010"/>
      <stop offset="100%" style="stop-color:#051008"/>
    </linearGradient>
    <!-- Packet animation paths -->
    <marker id="arrowCyan" markerWidth="6" markerHeight="6" refX="3" refY="3" orient="auto">
      <path d="M0,0 L0,6 L6,3 z" fill="#00f5ff" opacity="0.8"/>
    </marker>
    <marker id="arrowMagenta" markerWidth="6" markerHeight="6" refX="3" refY="3" orient="auto">
      <path d="M0,0 L0,6 L6,3 z" fill="#ff00c8" opacity="0.8"/>
    </marker>
  </defs>

  <rect width="900" height="420" fill="url(#infraBg)" rx="0"/>
  <rect width="900" height="420" fill="url(#grid2)"/>

  <!-- Title -->
  <text x="450" y="32" font-family="'Courier New', monospace" font-size="12" fill="#00f5ff" text-anchor="middle" letter-spacing="6" filter="url(#glow2)">◈ LIVE INFRASTRUCTURE VISUALIZATION ◈</text>
  <line x1="50" y1="42" x2="850" y2="42" stroke="#00f5ff" stroke-width="0.5" opacity="0.3"/>

  <!-- ══ USERS NODE ══ -->
  <g>
    <rect x="350" y="58" width="200" height="60" rx="8" fill="url(#nodeGrad1)" stroke="#00f5ff" stroke-width="1.5" filter="url(#glow2)">
      <animate attributeName="stroke-width" values="1.5;2.5;1.5" dur="3s" repeatCount="indefinite"/>
    </rect>
    <!-- Corner decorations -->
    <line x1="350" y1="66" x2="360" y2="58" stroke="#00f5ff" stroke-width="1.5"/>
    <line x1="542" y1="58" x2="550" y2="66" stroke="#00f5ff" stroke-width="1.5"/>
    <line x1="350" y1="110" x2="360" y2="118" stroke="#00f5ff" stroke-width="1.5"/>
    <line x1="542" y1="118" x2="550" y2="110" stroke="#00f5ff" stroke-width="1.5"/>
    <!-- Icon area -->
    <rect x="360" y="66" width="30" height="44" rx="3" fill="rgba(0,245,255,0.1)"/>
    <!-- User icons -->
    <circle cx="375" cy="80" r="7" fill="none" stroke="#00f5ff" stroke-width="1.2"/>
    <path d="M 363 104 Q 375 94 387 104" fill="none" stroke="#00f5ff" stroke-width="1.2"/>
    <!-- Text -->
    <text x="450" y="83" font-family="'Courier New', monospace" font-size="13" fill="#00f5ff" text-anchor="middle" font-weight="bold" letter-spacing="2">CLIENT USERS</text>
    <text x="450" y="103" font-family="'Courier New', monospace" font-size="9" fill="#00f5ff" text-anchor="middle" opacity="0.7">HTTP/HTTPS REQUESTS</text>
    <!-- Status dot -->
    <circle cx="530" cy="75" r="5" fill="#00ff88" filter="url(#glow2)"><animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/></circle>
    <text x="520" y="79" font-family="'Courier New', monospace" font-size="7" fill="#00ff88" text-anchor="end" opacity="0.8">LIVE</text>
  </g>

  <!-- Connection line: Users → Spring Boot -->
  <line x1="450" y1="118" x2="450" y2="155" stroke="#00f5ff" stroke-width="1" stroke-dasharray="4,4" opacity="0.5"/>

  <!-- Animated packets: Users → Spring Boot -->
  <circle r="4" fill="#00f5ff" filter="url(#glow2)">
    <animateMotion path="M 450 118 L 450 155" dur="1.2s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.2s" repeatCount="indefinite" begin="0s"/>
  </circle>
  <circle r="4" fill="#00f5ff" filter="url(#glow2)">
    <animateMotion path="M 450 118 L 450 155" dur="1.2s" repeatCount="indefinite" begin="0.6s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.2s" repeatCount="indefinite" begin="0.6s"/>
  </circle>

  <!-- ══ SPRING BOOT NODE ══ -->
  <g>
    <rect x="300" y="158" width="300" height="70" rx="8" fill="url(#nodeGrad3)" stroke="#6DB33F" stroke-width="1.5" filter="url(#glow2)">
      <animate attributeName="stroke-width" values="1.5;2.5;1.5" dur="2.8s" repeatCount="indefinite"/>
    </rect>
    <line x1="300" y1="166" x2="310" y2="158" stroke="#6DB33F" stroke-width="1.5"/>
    <line x1="592" y1="158" x2="600" y2="166" stroke="#6DB33F" stroke-width="1.5"/>
    <line x1="300" y1="220" x2="310" y2="228" stroke="#6DB33F" stroke-width="1.5"/>
    <line x1="592" y1="228" x2="600" y2="220" stroke="#6DB33F" stroke-width="1.5"/>
    <!-- Spring leaf icon -->
    <circle cx="320" cy="188" r="14" fill="rgba(109,179,63,0.15)" stroke="#6DB33F" stroke-width="1"/>
    <path d="M 314 194 Q 318 182 328 184 Q 324 196 314 194 Z" fill="#6DB33F" opacity="0.8"/>
    <path d="M 314 194 Q 320 190 322 184" fill="none" stroke="#6DB33F" stroke-width="1"/>
    <!-- Text -->
    <text x="450" y="186" font-family="'Courier New', monospace" font-size="14" fill="#6DB33F" text-anchor="middle" font-weight="bold" letter-spacing="1">SPRING BOOT API LAYER</text>
    <text x="450" y="204" font-family="'Courier New', monospace" font-size="9" fill="#6DB33F" text-anchor="middle" opacity="0.7">JWT AUTH  ·  REST  ·  RATE LIMITING  ·  MIDDLEWARE</text>
    <text x="450" y="220" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.8">◉ 847 req/s  ·  p99: 12ms  ·  ERR: 0.01%</text>
    <circle cx="580" cy="175" r="5" fill="#00ff88" filter="url(#glow2)"><animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Connection lines: Spring Boot → Redis & MySQL -->
  <!-- Left: Spring Boot → Redis -->
  <path d="M 380 228 Q 260 250 230 268" fill="none" stroke="#DC382D" stroke-width="1" stroke-dasharray="4,4" opacity="0.6"/>
  <!-- Right: Spring Boot → MySQL -->
  <path d="M 520 228 Q 640 250 670 268" fill="none" stroke="#00758F" stroke-width="1" stroke-dasharray="4,4" opacity="0.6"/>

  <!-- Packets: Spring Boot → Redis -->
  <circle r="4" fill="#DC382D" filter="url(#glow2)">
    <animateMotion path="M 380 228 Q 260 250 230 268" dur="1.5s" repeatCount="indefinite" begin="0.2s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.5s" repeatCount="indefinite" begin="0.2s"/>
  </circle>
  <circle r="4" fill="#DC382D" filter="url(#glow2)">
    <animateMotion path="M 380 228 Q 260 250 230 268" dur="1.5s" repeatCount="indefinite" begin="0.95s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.5s" repeatCount="indefinite" begin="0.95s"/>
  </circle>

  <!-- Packets: Spring Boot → MySQL -->
  <circle r="4" fill="#00758F" filter="url(#glow2)">
    <animateMotion path="M 520 228 Q 640 250 670 268" dur="1.8s" repeatCount="indefinite" begin="0.4s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.8s" repeatCount="indefinite" begin="0.4s"/>
  </circle>
  <circle r="4" fill="#00758F" filter="url(#glow2)">
    <animateMotion path="M 520 228 Q 640 250 670 268" dur="1.8s" repeatCount="indefinite" begin="1.3s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.8s" repeatCount="indefinite" begin="1.3s"/>
  </circle>

  <!-- ══ REDIS NODE ══ -->
  <g>
    <rect x="100" y="268" width="260" height="65" rx="8" fill="#150808" stroke="#DC382D" stroke-width="1.5" filter="url(#glow2)">
      <animate attributeName="stroke-width" values="1.5;2.5;1.5" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <line x1="100" y1="276" x2="110" y2="268" stroke="#DC382D" stroke-width="1.5"/>
    <line x1="352" y1="268" x2="360" y2="276" stroke="#DC382D" stroke-width="1.5"/>
    <line x1="100" y1="325" x2="110" y2="333" stroke="#DC382D" stroke-width="1.5"/>
    <line x1="352" y1="333" x2="360" y2="325" stroke="#DC382D" stroke-width="1.5"/>
    <!-- Redis icon suggestion -->
    <rect x="112" y="278" width="30" height="44" rx="15" fill="rgba(220,56,45,0.15)" stroke="#DC382D" stroke-width="1"/>
    <text x="127" y="305" font-family="'Courier New', monospace" font-size="9" fill="#DC382D" text-anchor="middle">R</text>
    <!-- Text -->
    <text x="230" y="295" font-family="'Courier New', monospace" font-size="13" fill="#DC382D" text-anchor="middle" font-weight="bold" letter-spacing="1">REDIS CACHE</text>
    <text x="230" y="312" font-family="'Courier New', monospace" font-size="9" fill="#DC382D" text-anchor="middle" opacity="0.7">IN-MEMORY  ·  SUB-MILLISECOND</text>
    <text x="230" y="326" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.8">◉ HIT RATE: 94.7%  ·  3.2ms avg</text>
    <circle cx="348" cy="280" r="5" fill="#00ff88" filter="url(#glow2)"><animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ══ MYSQL NODE ══ -->
  <g>
    <rect x="540" y="268" width="260" height="65" rx="8" fill="#050f14" stroke="#00758F" stroke-width="1.5" filter="url(#glow2)">
      <animate attributeName="stroke-width" values="1.5;2.5;1.5" dur="3.2s" repeatCount="indefinite"/>
    </rect>
    <line x1="540" y1="276" x2="550" y2="268" stroke="#00758F" stroke-width="1.5"/>
    <line x1="792" y1="268" x2="800" y2="276" stroke="#00758F" stroke-width="1.5"/>
    <line x1="540" y1="325" x2="550" y2="333" stroke="#00758F" stroke-width="1.5"/>
    <line x1="792" y1="333" x2="800" y2="325" stroke="#00758F" stroke-width="1.5"/>
    <!-- DB icon -->
    <ellipse cx="562" cy="286" rx="12" ry="5" fill="rgba(0,117,143,0.3)" stroke="#00758F" stroke-width="1"/>
    <rect x="550" y="286" width="24" height="20" fill="rgba(0,117,143,0.15)"/>
    <ellipse cx="562" cy="306" rx="12" ry="5" fill="rgba(0,117,143,0.2)" stroke="#00758F" stroke-width="1"/>
    <!-- Text -->
    <text x="670" y="295" font-family="'Courier New', monospace" font-size="13" fill="#00758F" text-anchor="middle" font-weight="bold" letter-spacing="1">MYSQL DATABASE</text>
    <text x="670" y="312" font-family="'Courier New', monospace" font-size="9" fill="#00758F" text-anchor="middle" opacity="0.7">RELATIONAL  ·  ACID  ·  INDEXED</text>
    <text x="670" y="326" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.8">◉ 1.2M rows  ·  QPS: 340  ·  UP: 99.9%</text>
    <circle cx="788" cy="280" r="5" fill="#00ff88" filter="url(#glow2)"><animate attributeName="opacity" values="1;0.3;1" dur="2.1s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Connection lines: Redis & MySQL → AWS -->
  <path d="M 230 333 Q 250 370 380 380" fill="none" stroke="#FF9900" stroke-width="1" stroke-dasharray="4,4" opacity="0.6"/>
  <path d="M 670 333 Q 650 370 520 380" fill="none" stroke="#FF9900" stroke-width="1" stroke-dasharray="4,4" opacity="0.6"/>

  <!-- Packets: → AWS -->
  <circle r="4" fill="#FF9900" filter="url(#glow2)">
    <animateMotion path="M 230 333 Q 250 370 380 380" dur="1.6s" repeatCount="indefinite" begin="0.5s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.6s" repeatCount="indefinite" begin="0.5s"/>
  </circle>
  <circle r="4" fill="#FF9900" filter="url(#glow2)">
    <animateMotion path="M 670 333 Q 650 370 520 380" dur="1.6s" repeatCount="indefinite" begin="0.8s"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="1.6s" repeatCount="indefinite" begin="0.8s"/>
  </circle>

  <!-- ══ AWS NODE ══ -->
  <g>
    <rect x="250" y="370" width="400" height="38" rx="8" fill="#120c00" stroke="#FF9900" stroke-width="1.5" filter="url(#glow2)">
      <animate attributeName="stroke-width" values="1.5;3;1.5" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.8;1;0.8" dur="2s" repeatCount="indefinite"/>
    </rect>
    <line x1="250" y1="378" x2="262" y2="370" stroke="#FF9900" stroke-width="1.5"/>
    <line x1="638" y1="370" x2="650" y2="378" stroke="#FF9900" stroke-width="1.5"/>
    <line x1="250" y1="400" x2="262" y2="408" stroke="#FF9900" stroke-width="1.5"/>
    <line x1="638" y1="408" x2="650" y2="400" stroke="#FF9900" stroke-width="1.5"/>
    <!-- Text -->
    <text x="450" y="390" font-family="'Courier New', monospace" font-size="12" fill="#FF9900" text-anchor="middle" font-weight="bold" letter-spacing="3">☁  AWS CLOUD INFRASTRUCTURE  ☁</text>
    <text x="450" y="404" font-family="'Courier New', monospace" font-size="8" fill="#FF9900" text-anchor="middle" opacity="0.7">EC2  ·  RDS  ·  ELASTICACHE  ·  ECS  ·  CLOUDWATCH</text>
    <!-- Pulse rings -->
    <circle cx="280" cy="389" r="8" fill="none" stroke="#FF9900" stroke-width="1" opacity="0.6"><animate attributeName="r" values="8;14;8" dur="2s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.6;0;0.6" dur="2s" repeatCount="indefinite"/></circle>
    <circle cx="280" cy="389" r="4" fill="#FF9900" opacity="0.6" filter="url(#glow2)"/>
    <circle cx="620" cy="389" r="8" fill="none" stroke="#FF9900" stroke-width="1" opacity="0.6"><animate attributeName="r" values="8;14;8" dur="2s" repeatCount="indefinite" begin="1s"/><animate attributeName="opacity" values="0.6;0;0.6" dur="2s" repeatCount="indefinite" begin="1s"/></circle>
    <circle cx="620" cy="389" r="4" fill="#FF9900" opacity="0.6" filter="url(#glow2)"/>
  </g>

  <!-- Bottom status bar -->
  <rect x="20" y="412" width="860" height="4" rx="2" fill="rgba(0,245,255,0.1)"/>
  <rect x="20" y="412" width="200" height="4" rx="2" fill="#00f5ff" opacity="0.5"><animate attributeName="width" values="200;700;200" dur="5s" repeatCount="indefinite"/></rect>
</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                   GITHUB STATS ZONE                          -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="36" viewBox="0 0 900 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="900" height="36" fill="#020818"/>
  <text x="450" y="23" font-family="'Courier New', monospace" font-size="12" fill="#00f5ff" text-anchor="middle" letter-spacing="6">◈ GITHUB COMMAND STATS ◈</text>
  <line x1="50" y1="30" x2="850" y2="30" stroke="#00f5ff" stroke-width="0.5" opacity="0.3"/>
</svg>

<a href="https://github.com/sanjayvrd">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=sanjayvrd&show_icons=true&theme=tokyo-night&include_all_commits=true&count_private=true&hide_border=true&bg_color=020818&title_color=00f5ff&icon_color=ff00c8&text_color=c0caf5&ring_color=ff00c8"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjayvrd&layout=compact&langs_count=8&theme=tokyo-night&hide_border=true&bg_color=020818&title_color=00f5ff&text_color=c0caf5"/>
</a>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sanjayvrd&theme=tokyo-night&hide_border=true&background=020818&stroke=00f5ff&ring=ff00c8&fire=ffd700&currStreakLabel=00f5ff&sideLabels=00f5ff&currStreakNum=ffffff&sideNums=c0caf5&dates=6b7db3" alt="GitHub Streak"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sanjayvrd&bg_color=020818&color=00f5ff&line=ff00c8&point=ffd700&area_color=00f5ff&area=true&hide_border=true" alt="Contribution Graph"/>

<br/>

<!-- Contribution Snake -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sanjayvrd/sanjayvrd/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sanjayvrd/sanjayvrd/output/github-contribution-grid-snake.svg"/>
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/sanjayvrd/sanjayvrd/output/github-contribution-grid-snake-dark.svg"/>
</picture>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                AI SECURITY CENTER PANEL                      -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="340" viewBox="0 0 900 340" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#02080e"/>
      <stop offset="100%" style="stop-color:#080218"/>
    </linearGradient>
    <filter id="secGlow"><feGaussianBlur stdDeviation="4" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <pattern id="secGrid" x="0" y="0" width="25" height="25" patternUnits="userSpaceOnUse">
      <path d="M 25 0 L 0 0 0 25" fill="none" stroke="rgba(255,0,200,0.04)" stroke-width="0.5"/>
    </pattern>
    <!-- Gauge gradient -->
    <linearGradient id="gaugeGrad" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff0040"/>
      <stop offset="50%" style="stop-color:#ffd700"/>
      <stop offset="100%" style="stop-color:#00ff88"/>
    </linearGradient>
    <!-- Red threat gradient -->
    <linearGradient id="threatGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff0040"/>
      <stop offset="100%" style="stop-color:#ff6600"/>
    </linearGradient>
    <!-- Progress gradient -->
    <linearGradient id="scoreGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff0040"/>
      <stop offset="70%" style="stop-color:#ffd700"/>
      <stop offset="100%" style="stop-color:#ff0040"/>
    </linearGradient>
  </defs>

  <rect width="900" height="340" fill="url(#secBg)"/>
  <rect width="900" height="340" fill="url(#secGrid)"/>

  <!-- Scan line effect -->
  <rect width="900" height="2" fill="rgba(255,0,200,0.15)" y="0">
    <animate attributeName="y" values="0;340;0" dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- Header -->
  <text x="450" y="28" font-family="'Courier New', monospace" font-size="12" fill="#ff00c8" text-anchor="middle" letter-spacing="6" filter="url(#secGlow)">◈ AI EMAIL FRAUD DETECTION CENTER ◈</text>
  <line x1="50" y1="38" x2="850" y2="38" stroke="#ff00c8" stroke-width="0.5" opacity="0.4"/>

  <!-- ══ THREAT DETECTION GAUGE (left) ══ -->
  <!-- Circular gauge - threat level -->
  <g>
    <!-- Gauge background arc -->
    <path d="M 120 180 A 80 80 0 0 1 280 180" fill="none" stroke="rgba(255,0,64,0.15)" stroke-width="16" stroke-linecap="round"/>
    <!-- Gauge fill - animated -->
    <path d="M 120 180 A 80 80 0 0 1 200 100" fill="none" stroke="url(#threatGrad)" stroke-width="16" stroke-linecap="round" filter="url(#secGlow)">
      <animateTransform attributeName="transform" type="rotate" values="0,200,180;5,200,180;-3,200,180;0,200,180" dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Tick marks -->
    <line x1="120" y1="180" x2="128" y2="180" stroke="#ff0040" stroke-width="2" opacity="0.6"/>
    <line x1="200" y1="100" x2="200" y2="108" stroke="#ffd700" stroke-width="2" opacity="0.6"/>
    <line x1="280" y1="180" x2="272" y2="180" stroke="#00ff88" stroke-width="2" opacity="0.6"/>
    <!-- Needle -->
    <line x1="200" y1="180" x2="145" y2="130" stroke="#ff0040" stroke-width="2.5" stroke-linecap="round" filter="url(#secGlow)">
      <animateTransform attributeName="transform" type="rotate" values="0,200,180;8,200,180;-5,200,180;3,200,180;0,200,180" dur="4s" repeatCount="indefinite"/>
    </line>
    <circle cx="200" cy="180" r="8" fill="#ff0040" filter="url(#secGlow)"><animate attributeName="opacity" values="1;0.6;1" dur="1.5s" repeatCount="indefinite"/></circle>
    <!-- Labels -->
    <text x="200" y="210" font-family="'Courier New', monospace" font-size="10" fill="#ff00c8" text-anchor="middle">THREAT LEVEL</text>
    <text x="200" y="228" font-family="'Courier New', monospace" font-size="20" fill="#ff0040" text-anchor="middle" font-weight="bold" filter="url(#secGlow)">HIGH</text>
    <text x="200" y="246" font-family="'Courier New', monospace" font-size="9" fill="#ff0040" text-anchor="middle" opacity="0.7">ACTIVE MONITORING</text>
    <!-- Side labels -->
    <text x="108" y="186" font-family="'Courier New', monospace" font-size="8" fill="#ff0040" text-anchor="end">CRIT</text>
    <text x="292" y="186" font-family="'Courier New', monospace" font-size="8" fill="#00ff88">SAFE</text>
  </g>

  <!-- ══ FRAUD CONFIDENCE SCORE (center) ══ -->
  <g>
    <!-- Panel background -->
    <rect x="310" y="55" width="280" height="260" rx="8" fill="rgba(255,0,200,0.05)" stroke="#ff00c8" stroke-width="1" opacity="0.8"/>
    <line x1="310" y1="63" x2="320" y2="55" stroke="#ff00c8" stroke-width="1.5"/>
    <line x1="582" y1="55" x2="590" y2="63" stroke="#ff00c8" stroke-width="1.5"/>

    <text x="450" y="78" font-family="'Courier New', monospace" font-size="10" fill="#ff00c8" text-anchor="middle" letter-spacing="3">FRAUD CONFIDENCE SCORE</text>

    <!-- Big score number - animated -->
    <text x="450" y="135" font-family="'Courier New', monospace" font-size="52" fill="#ffd700" text-anchor="middle" font-weight="bold" filter="url(#secGlow)">
      87.3
      <animate attributeName="opacity" values="1;0.85;1" dur="2.5s" repeatCount="indefinite"/>
    </text>
    <text x="450" y="155" font-family="'Courier New', monospace" font-size="11" fill="#ffd700" text-anchor="middle" opacity="0.7">PERCENT CERTAINTY</text>

    <!-- Progress bars - email features -->
    <!-- Sender Score -->
    <text x="325" y="180" font-family="'Courier New', monospace" font-size="8" fill="#ff00c8" opacity="0.8">SENDER SCORE</text>
    <text x="585" y="180" font-family="'Courier New', monospace" font-size="8" fill="#ff0040" text-anchor="end">SUSPICIOUS</text>
    <rect x="325" y="183" width="255" height="6" rx="3" fill="rgba(255,0,200,0.1)"/>
    <rect x="325" y="183" width="180" height="6" rx="3" fill="#ff0040" filter="url(#secGlow)"><animate attributeName="width" values="180;195;175;180" dur="3s" repeatCount="indefinite"/></rect>

    <!-- Header Analysis -->
    <text x="325" y="204" font-family="'Courier New', monospace" font-size="8" fill="#ff00c8" opacity="0.8">HEADER ANALYSIS</text>
    <text x="585" y="204" font-family="'Courier New', monospace" font-size="8" fill="#ffd700" text-anchor="end">ANOMALY</text>
    <rect x="325" y="207" width="255" height="6" rx="3" fill="rgba(255,0,200,0.1)"/>
    <rect x="325" y="207" width="215" height="6" rx="3" fill="#ffd700"><animate attributeName="width" values="215;225;210;215" dur="4s" repeatCount="indefinite"/></rect>

    <!-- Link Analysis -->
    <text x="325" y="228" font-family="'Courier New', monospace" font-size="8" fill="#ff00c8" opacity="0.8">LINK ANALYSIS</text>
    <text x="585" y="228" font-family="'Courier New', monospace" font-size="8" fill="#ff0040" text-anchor="end">MALICIOUS</text>
    <rect x="325" y="231" width="255" height="6" rx="3" fill="rgba(255,0,200,0.1)"/>
    <rect x="325" y="231" width="230" height="6" rx="3" fill="#ff0040" filter="url(#secGlow)"><animate attributeName="width" values="230;245;225;230" dur="2.5s" repeatCount="indefinite"/></rect>

    <!-- NLP Toxicity -->
    <text x="325" y="252" font-family="'Courier New', monospace" font-size="8" fill="#ff00c8" opacity="0.8">NLP TOXICITY</text>
    <text x="585" y="252" font-family="'Courier New', monospace" font-size="8" fill="#ffd700" text-anchor="end">MODERATE</text>
    <rect x="325" y="255" width="255" height="6" rx="3" fill="rgba(255,0,200,0.1)"/>
    <rect x="325" y="255" width="140" height="6" rx="3" fill="#ffd700"><animate attributeName="width" values="140;155;135;140" dur="3.5s" repeatCount="indefinite"/></rect>

    <!-- Verdict -->
    <rect x="325" y="275" width="255" height="28" rx="4" fill="rgba(255,0,64,0.2)" stroke="#ff0040" stroke-width="1">
      <animate attributeName="stroke-opacity" values="1;0.4;1" dur="1s" repeatCount="indefinite"/>
    </rect>
    <text x="452" y="294" font-family="'Courier New', monospace" font-size="11" fill="#ff0040" text-anchor="middle" font-weight="bold" filter="url(#secGlow)">⚠ FRAUD DETECTED — QUARANTINE</text>
  </g>

  <!-- ══ SECURITY STATUS PANEL (right) ══ -->
  <g>
    <!-- Status items -->
    <text x="720" y="68" font-family="'Courier New', monospace" font-size="10" fill="#ff00c8" text-anchor="middle" letter-spacing="3">SECURITY STATUS</text>

    <!-- AI Model -->
    <rect x="620" y="80" width="200" height="30" rx="4" fill="rgba(0,255,136,0.08)" stroke="#00ff88" stroke-width="0.8"/>
    <circle cx="636" cy="95" r="5" fill="#00ff88" filter="url(#secGlow)"><animate attributeName="opacity" values="1;0.4;1" dur="1.2s" repeatCount="indefinite"/></circle>
    <text x="648" y="99" font-family="'Courier New', monospace" font-size="9" fill="#00ff88">AI MODEL  ·  ONLINE</text>

    <!-- Fraud DB -->
    <rect x="620" y="118" width="200" height="30" rx="4" fill="rgba(0,255,136,0.08)" stroke="#00ff88" stroke-width="0.8"/>
    <circle cx="636" cy="133" r="5" fill="#00ff88" filter="url(#secGlow)"><animate attributeName="opacity" values="1;0.4;1" dur="1.8s" repeatCount="indefinite"/></circle>
    <text x="648" y="137" font-family="'Courier New', monospace" font-size="9" fill="#00ff88">FRAUD DB  ·  SYNCED</text>

    <!-- API Gateway -->
    <rect x="620" y="156" width="200" height="30" rx="4" fill="rgba(0,255,136,0.08)" stroke="#00ff88" stroke-width="0.8"/>
    <circle cx="636" cy="171" r="5" fill="#00ff88" filter="url(#secGlow)"><animate attributeName="opacity" values="1;0.4;1" dur="2.1s" repeatCount="indefinite"/></circle>
    <text x="648" y="175" font-family="'Courier New', monospace" font-size="9" fill="#00ff88">API GATEWAY  ·  SECURED</text>

    <!-- Alert queue -->
    <rect x="620" y="194" width="200" height="30" rx="4" fill="rgba(255,215,0,0.08)" stroke="#ffd700" stroke-width="0.8"/>
    <circle cx="636" cy="209" r="5" fill="#ffd700"><animate attributeName="opacity" values="1;0.3;1" dur="0.8s" repeatCount="indefinite"/></circle>
    <text x="648" y="213" font-family="'Courier New', monospace" font-size="9" fill="#ffd700">ALERT QUEUE  ·  3 ACTIVE</text>

    <!-- Quarantine -->
    <rect x="620" y="232" width="200" height="30" rx="4" fill="rgba(255,0,64,0.08)" stroke="#ff0040" stroke-width="0.8"/>
    <circle cx="636" cy="247" r="5" fill="#ff0040" filter="url(#secGlow)"><animate attributeName="opacity" values="1;0.3;1" dur="0.5s" repeatCount="indefinite"/></circle>
    <text x="648" y="251" font-family="'Courier New', monospace" font-size="9" fill="#ff0040">QUARANTINE  ·  14 BLOCKED</text>

    <!-- Emails today counter -->
    <rect x="620" y="275" width="200" height="45" rx="4" fill="rgba(255,0,200,0.08)" stroke="#ff00c8" stroke-width="1"/>
    <text x="720" y="293" font-family="'Courier New', monospace" font-size="9" fill="#ff00c8" text-anchor="middle" opacity="0.7">EMAILS ANALYZED TODAY</text>
    <text x="720" y="313" font-family="'Courier New', monospace" font-size="22" fill="#ff00c8" text-anchor="middle" font-weight="bold" filter="url(#secGlow)">24,871</text>
  </g>

</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                   IAM CONTROL ROOM                           -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="340" viewBox="0 0 900 340" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="iamBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020e18"/>
      <stop offset="100%" style="stop-color:#02180e"/>
    </linearGradient>
    <filter id="iamGlow"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <pattern id="iamGrid" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="rgba(0,255,136,0.04)" stroke-width="0.5"/>
    </pattern>
    <!-- JWT token gradient -->
    <linearGradient id="jwtGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff0040"/>
      <stop offset="33%" style="stop-color:#ff0040"/>
      <stop offset="33%" style="stop-color:#9900ff"/>
      <stop offset="66%" style="stop-color:#9900ff"/>
      <stop offset="66%" style="stop-color:#00ff88"/>
      <stop offset="100%" style="stop-color:#00ff88"/>
    </linearGradient>
  </defs>

  <rect width="900" height="340" fill="url(#iamBg)"/>
  <rect width="900" height="340" fill="url(#iamGrid)"/>

  <!-- Header -->
  <text x="450" y="28" font-family="'Courier New', monospace" font-size="12" fill="#00ff88" text-anchor="middle" letter-spacing="6" filter="url(#iamGlow)">◈ IAM BACKEND CONTROL ROOM ◈</text>
  <line x1="50" y1="38" x2="850" y2="38" stroke="#00ff88" stroke-width="0.5" opacity="0.4"/>

  <!-- ══ JWT TOKEN FLOW ══ -->
  <text x="450" y="62" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" text-anchor="middle" opacity="0.6" letter-spacing="4">JWT TOKEN PIPELINE</text>

  <!-- Token flow line -->
  <line x1="60" y1="90" x2="840" y2="90" stroke="rgba(0,255,136,0.2)" stroke-width="20" rx="10"/>
  <line x1="60" y1="90" x2="840" y2="90" stroke="rgba(0,255,136,0.05)" stroke-width="22" rx="11"/>

  <!-- JWT tokens flowing -->
  <!-- Token 1 -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 780,0; 780,0" dur="5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1; 0 0 0 0"/>
    <rect x="60" y="76" width="80" height="28" rx="4" fill="rgba(0,0,0,0.8)" stroke="url(#jwtGrad)" stroke-width="1.5" filter="url(#iamGlow)"/>
    <rect x="60" y="76" width="26" height="28" rx="4" fill="rgba(255,0,64,0.3)"/>
    <rect x="86" y="76" width="28" height="28" fill="rgba(153,0,255,0.3)"/>
    <rect x="114" y="76" width="26" height="28" rx="4" fill="rgba(0,255,136,0.3)"/>
    <text x="73" y="94" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle">hdr</text>
    <text x="100" y="94" font-family="'Courier New', monospace" font-size="7" fill="#9900ff" text-anchor="middle">pld</text>
    <text x="127" y="94" font-family="'Courier New', monospace" font-size="7" fill="#00ff88" text-anchor="middle">sig</text>
  </g>

  <!-- Token 2 -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 780,0; 780,0" dur="5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1; 0 0 0 0" begin="1.5s"/>
    <rect x="60" y="76" width="80" height="28" rx="4" fill="rgba(0,0,0,0.8)" stroke="url(#jwtGrad)" stroke-width="1.5" filter="url(#iamGlow)"/>
    <rect x="60" y="76" width="26" height="28" rx="4" fill="rgba(255,0,64,0.3)"/>
    <rect x="86" y="76" width="28" height="28" fill="rgba(153,0,255,0.3)"/>
    <rect x="114" y="76" width="26" height="28" rx="4" fill="rgba(0,255,136,0.3)"/>
    <text x="73" y="94" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle">hdr</text>
    <text x="100" y="94" font-family="'Courier New', monospace" font-size="7" fill="#9900ff" text-anchor="middle">pld</text>
    <text x="127" y="94" font-family="'Courier New', monospace" font-size="7" fill="#00ff88" text-anchor="middle">sig</text>
  </g>

  <!-- Token 3 -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 780,0; 780,0" dur="5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1; 0 0 0 0" begin="3s"/>
    <rect x="60" y="76" width="80" height="28" rx="4" fill="rgba(0,0,0,0.8)" stroke="url(#jwtGrad)" stroke-width="1.5" filter="url(#iamGlow)"/>
    <rect x="60" y="76" width="26" height="28" rx="4" fill="rgba(255,0,64,0.3)"/>
    <rect x="86" y="76" width="28" height="28" fill="rgba(153,0,255,0.3)"/>
    <rect x="114" y="76" width="26" height="28" rx="4" fill="rgba(0,255,136,0.3)"/>
    <text x="73" y="94" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle">hdr</text>
    <text x="100" y="94" font-family="'Courier New', monospace" font-size="7" fill="#9900ff" text-anchor="middle">pld</text>
    <text x="127" y="94" font-family="'Courier New', monospace" font-size="7" fill="#00ff88" text-anchor="middle">sig</text>
  </g>

  <!-- Flow label -->
  <text x="450" y="115" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.5">header.payload.signature  →  SIGNED WITH RS256  →  EXPIRES IN 3600s</text>

  <!-- ══ RBAC ROLE DIAGRAM ══ -->
  <text x="450" y="145" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" text-anchor="middle" opacity="0.6" letter-spacing="4">ROLE-BASED ACCESS CONTROL</text>

  <!-- Central IAM Hub -->
  <circle cx="450" cy="230" r="35" fill="rgba(0,255,136,0.08)" stroke="#00ff88" stroke-width="2" filter="url(#iamGlow)">
    <animate attributeName="stroke-width" values="2;3;2" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="230" r="28" fill="rgba(0,255,136,0.05)" stroke="#00ff88" stroke-width="0.5" opacity="0.5"/>
  <text x="450" y="225" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" text-anchor="middle" font-weight="bold">IAM</text>
  <text x="450" y="237" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.7">ENGINE</text>

  <!-- ADMIN node -->
  <circle cx="200" cy="210" r="45" fill="rgba(255,0,64,0.08)" stroke="#ff0040" stroke-width="1.5" filter="url(#iamGlow)"/>
  <text x="200" y="200" font-family="'Courier New', monospace" font-size="11" fill="#ff0040" text-anchor="middle" font-weight="bold">ADMIN</text>
  <text x="200" y="215" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle" opacity="0.7">ALL PERMISSIONS</text>
  <text x="200" y="228" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle" opacity="0.6">READ  WRITE  DELETE</text>
  <text x="200" y="241" font-family="'Courier New', monospace" font-size="7" fill="#ff0040" text-anchor="middle" opacity="0.6">EXECUTE  MANAGE</text>
  <!-- Glow ring -->
  <circle cx="200" cy="210" r="48" fill="none" stroke="#ff0040" stroke-width="1" opacity="0.3">
    <animate attributeName="r" values="48;55;48" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- MANAGER node -->
  <circle cx="450" cy="310" r="40" fill="rgba(255,215,0,0.08)" stroke="#ffd700" stroke-width="1.5" filter="url(#iamGlow)"/>
  <text x="450" y="302" font-family="'Courier New', monospace" font-size="11" fill="#ffd700" text-anchor="middle" font-weight="bold">MANAGER</text>
  <text x="450" y="316" font-family="'Courier New', monospace" font-size="7" fill="#ffd700" text-anchor="middle" opacity="0.7">PARTIAL ACCESS</text>
  <text x="450" y="329" font-family="'Courier New', monospace" font-size="7" fill="#ffd700" text-anchor="middle" opacity="0.6">READ  WRITE  EXECUTE</text>

  <!-- USER node -->
  <circle cx="700" cy="210" r="40" fill="rgba(0,150,255,0.08)" stroke="#0096ff" stroke-width="1.5" filter="url(#iamGlow)"/>
  <text x="700" y="202" font-family="'Courier New', monospace" font-size="11" fill="#0096ff" text-anchor="middle" font-weight="bold">USER</text>
  <text x="700" y="217" font-family="'Courier New', monospace" font-size="7" fill="#0096ff" text-anchor="middle" opacity="0.7">LIMITED ACCESS</text>
  <text x="700" y="230" font-family="'Courier New', monospace" font-size="7" fill="#0096ff" text-anchor="middle" opacity="0.6">READ ONLY</text>

  <!-- Connecting lines with glow -->
  <!-- Admin → IAM -->
  <line x1="245" y1="210" x2="415" y2="225" stroke="#ff0040" stroke-width="1.5" stroke-dasharray="6,3" opacity="0.7" filter="url(#iamGlow)"/>
  <!-- Manager → IAM -->
  <line x1="450" y1="270" x2="450" y2="265" stroke="#ffd700" stroke-width="1.5" stroke-dasharray="6,3" opacity="0.7" filter="url(#iamGlow)"/>
  <!-- User → IAM -->
  <line x1="660" y1="212" x2="485" y2="222" stroke="#0096ff" stroke-width="1.5" stroke-dasharray="6,3" opacity="0.7" filter="url(#iamGlow)"/>

  <!-- Animated auth packets on lines -->
  <circle r="3" fill="#ff0040" filter="url(#iamGlow)">
    <animateMotion path="M 245 210 L 415 225" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle r="3" fill="#ffd700">
    <animateMotion path="M 450 270 L 450 265" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle r="3" fill="#0096ff" filter="url(#iamGlow)">
    <animateMotion path="M 660 212 L 485 222" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite"/>
  </circle>

</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                    CAT DATA CENTER                           -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="230" viewBox="0 0 900 230" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="catBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818"/>
      <stop offset="100%" style="stop-color:#08020e"/>
    </linearGradient>
    <filter id="catGlow"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>

  <rect width="900" height="230" fill="url(#catBg)"/>

  <!-- Header -->
  <text x="450" y="28" font-family="'Courier New', monospace" font-size="12" fill="#bf00ff" text-anchor="middle" letter-spacing="6">◈ CAT DATA CENTER — GUARDIANS ONLINE ◈</text>
  <line x1="50" y1="38" x2="850" y2="38" stroke="#bf00ff" stroke-width="0.5" opacity="0.4"/>

  <!-- ══ CACHE CAT - Redis Guardian ══ -->
  <g>
    <rect x="30" y="55" width="195" height="155" rx="8" fill="rgba(220,56,45,0.06)" stroke="#DC382D" stroke-width="1.2"/>
    <!-- Pixel cat -->
    <!-- Body -->
    <rect x="95" y="100" width="30" height="22" rx="4" fill="#DC382D" opacity="0.9"/>
    <!-- Head -->
    <rect x="98" y="82" width="24" height="22" rx="4" fill="#DC382D" opacity="0.9"/>
    <!-- Ears -->
    <polygon points="100,82 96,74 103,82" fill="#DC382D"/>
    <polygon points="117,82 121,74 114,82" fill="#DC382D"/>
    <!-- Eyes - animated blink -->
    <rect x="102" y="87" width="5" height="5" rx="2" fill="#ff0040"><animate attributeName="height" values="5;1;5" dur="3.5s" repeatCount="indefinite"/></rect>
    <rect x="113" y="87" width="5" height="5" rx="2" fill="#ff0040"><animate attributeName="height" values="5;1;5" dur="3.5s" repeatCount="indefinite" begin="0.1s"/></rect>
    <!-- Nose -->
    <rect x="109" y="96" width="3" height="2" rx="1" fill="#ffaaaa"/>
    <!-- Tail - wagging -->
    <path d="M 95 115 Q 80 110 82 98" fill="none" stroke="#DC382D" stroke-width="3" stroke-linecap="round">
      <animate attributeName="d" values="M 95 115 Q 80 110 82 98;M 95 115 Q 78 118 78 106;M 95 115 Q 80 110 82 98" dur="1s" repeatCount="indefinite"/>
    </path>
    <!-- Server rack under cat -->
    <rect x="75" y="122" width="70" height="40" rx="3" fill="rgba(220,56,45,0.15)" stroke="#DC382D" stroke-width="1"/>
    <rect x="78" y="125" width="64" height="8" rx="1" fill="rgba(220,56,45,0.3)"/>
    <rect x="78" y="136" width="64" height="8" rx="1" fill="rgba(220,56,45,0.2)"/>
    <rect x="78" y="147" width="64" height="8" rx="1" fill="rgba(220,56,45,0.25)"/>
    <!-- LED indicators -->
    <circle cx="134" cy="129" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="0.8s" repeatCount="indefinite"/></circle>
    <circle cx="134" cy="140" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/></circle>
    <circle cx="134" cy="151" r="2" fill="#ffd700"><animate attributeName="opacity" values="1;0.3;1" dur="0.6s" repeatCount="indefinite"/></circle>
    <!-- Label -->
    <text x="127" y="83" font-family="'Courier New', monospace" font-size="8" fill="#DC382D" text-anchor="middle">🐈 CACHE CAT</text>
    <text x="127" y="175" font-family="'Courier New', monospace" font-size="8" fill="#DC382D" text-anchor="middle">REDIS GUARDIAN</text>
    <text x="127" y="188" font-family="'Courier New', monospace" font-size="7" fill="#DC382D" text-anchor="middle" opacity="0.6">HIT RATE: 94.7%</text>
    <text x="127" y="200" font-family="'Courier New', monospace" font-size="7" fill="#DC382D" text-anchor="middle" opacity="0.6">LATENCY: 0.3ms</text>
  </g>

  <!-- ══ API CAT - Spring Boot Protector ══ -->
  <g>
    <rect x="250" y="55" width="195" height="155" rx="8" fill="rgba(109,179,63,0.06)" stroke="#6DB33F" stroke-width="1.2"/>
    <!-- Pixel cat with helmet -->
    <rect x="315" y="100" width="30" height="22" rx="4" fill="#6DB33F" opacity="0.9"/>
    <rect x="318" y="82" width="24" height="22" rx="4" fill="#6DB33F" opacity="0.9"/>
    <polygon points="320,82 316,74 323,82" fill="#6DB33F"/>
    <polygon points="337,82 341,74 334,82" fill="#6DB33F"/>
    <!-- Goggles -->
    <rect x="320" y="87" width="7" height="6" rx="2" fill="#00f5ff" opacity="0.4" stroke="#00f5ff" stroke-width="0.8"/>
    <rect x="329" y="87" width="7" height="6" rx="2" fill="#00f5ff" opacity="0.4" stroke="#00f5ff" stroke-width="0.8"/>
    <rect x="322" y="89" width="3" height="3" rx="1" fill="#00f5ff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="2s" repeatCount="indefinite"/></rect>
    <rect x="331" y="89" width="3" height="3" rx="1" fill="#00f5ff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="2s" repeatCount="indefinite" begin="0.2s"/></rect>
    <rect x="327" y="90" width="2" height="2" fill="#00f5ff" opacity="0.5"/>
    <!-- Nose -->
    <rect x="329" y="97" width="3" height="2" rx="1" fill="#aaffaa"/>
    <!-- Tail -->
    <path d="M 315 115 Q 300 112 302 100" fill="none" stroke="#6DB33F" stroke-width="3" stroke-linecap="round">
      <animate attributeName="d" values="M 315 115 Q 300 112 302 100;M 315 115 Q 298 120 298 108;M 315 115 Q 300 112 302 100" dur="1.2s" repeatCount="indefinite"/>
    </path>
    <!-- Server rack -->
    <rect x="295" y="122" width="70" height="40" rx="3" fill="rgba(109,179,63,0.15)" stroke="#6DB33F" stroke-width="1"/>
    <rect x="298" y="125" width="64" height="8" rx="1" fill="rgba(109,179,63,0.3)"/>
    <rect x="298" y="136" width="64" height="8" rx="1" fill="rgba(109,179,63,0.2)"/>
    <rect x="298" y="147" width="64" height="8" rx="1" fill="rgba(109,179,63,0.25)"/>
    <circle cx="354" cy="129" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="1.1s" repeatCount="indefinite"/></circle>
    <circle cx="354" cy="140" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="0.7s" repeatCount="indefinite"/></circle>
    <circle cx="354" cy="151" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/></circle>
    <!-- Label -->
    <text x="347" y="83" font-family="'Courier New', monospace" font-size="8" fill="#6DB33F" text-anchor="middle">🐈 API CAT</text>
    <text x="347" y="175" font-family="'Courier New', monospace" font-size="8" fill="#6DB33F" text-anchor="middle">SPRING PROTECTOR</text>
    <text x="347" y="188" font-family="'Courier New', monospace" font-size="7" fill="#6DB33F" text-anchor="middle" opacity="0.6">THROUGHPUT: 847/s</text>
    <text x="347" y="200" font-family="'Courier New', monospace" font-size="7" fill="#6DB33F" text-anchor="middle" opacity="0.6">UPTIME: 99.9%</text>
  </g>

  <!-- ══ CLOUD CAT - AWS Overseer ══ -->
  <g>
    <rect x="470" y="55" width="195" height="155" rx="8" fill="rgba(255,153,0,0.06)" stroke="#FF9900" stroke-width="1.2"/>
    <!-- Cat with cloud vibes -->
    <rect x="535" y="100" width="30" height="22" rx="4" fill="#FF9900" opacity="0.9"/>
    <rect x="538" y="82" width="24" height="22" rx="4" fill="#FF9900" opacity="0.9"/>
    <polygon points="540,82 536,74 543,82" fill="#FF9900"/>
    <polygon points="557,82 561,74 554,82" fill="#FF9900"/>
    <!-- Eyes - big -->
    <rect x="542" y="87" width="5" height="5" rx="2" fill="#ffd700"><animate attributeName="height" values="5;1;5" dur="4s" repeatCount="indefinite"/></rect>
    <rect x="553" y="87" width="5" height="5" rx="2" fill="#ffd700"><animate attributeName="height" values="5;1;5" dur="4s" repeatCount="indefinite" begin="0.1s"/></rect>
    <rect x="549" y="97" width="3" height="2" rx="1" fill="#ffddaa"/>
    <!-- Tail - lazy swish -->
    <path d="M 535 118 Q 520 110 525 100" fill="none" stroke="#FF9900" stroke-width="3" stroke-linecap="round">
      <animate attributeName="d" values="M 535 118 Q 520 110 525 100;M 535 118 Q 516 122 518 110;M 535 118 Q 520 110 525 100" dur="1.8s" repeatCount="indefinite"/>
    </path>
    <!-- Cloud shapes floating above cat -->
    <ellipse cx="550" cy="68" rx="18" ry="8" fill="rgba(255,153,0,0.2)" stroke="#FF9900" stroke-width="0.8">
      <animate attributeName="cy" values="68;65;68" dur="3s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="563" cy="70" rx="10" ry="6" fill="rgba(255,153,0,0.15)" stroke="#FF9900" stroke-width="0.8">
      <animate attributeName="cy" values="70;67;70" dur="2.5s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Server rack -->
    <rect x="515" y="122" width="70" height="40" rx="3" fill="rgba(255,153,0,0.15)" stroke="#FF9900" stroke-width="1"/>
    <rect x="518" y="125" width="64" height="8" rx="1" fill="rgba(255,153,0,0.3)"/>
    <rect x="518" y="136" width="64" height="8" rx="1" fill="rgba(255,153,0,0.2)"/>
    <rect x="518" y="147" width="64" height="8" rx="1" fill="rgba(255,153,0,0.25)"/>
    <circle cx="574" cy="129" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="0.9s" repeatCount="indefinite"/></circle>
    <circle cx="574" cy="140" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="1.4s" repeatCount="indefinite"/></circle>
    <circle cx="574" cy="151" r="2" fill="#ffd700"><animate attributeName="opacity" values="1;0.3;1" dur="1.1s" repeatCount="indefinite"/></circle>
    <!-- Label -->
    <text x="567" y="83" font-family="'Courier New', monospace" font-size="8" fill="#FF9900" text-anchor="middle">🐈 CLOUD CAT</text>
    <text x="567" y="175" font-family="'Courier New', monospace" font-size="8" fill="#FF9900" text-anchor="middle">AWS OVERSEER</text>
    <text x="567" y="188" font-family="'Courier New', monospace" font-size="7" fill="#FF9900" text-anchor="middle" opacity="0.6">REGIONS: 3 ACTIVE</text>
    <text x="567" y="200" font-family="'Courier New', monospace" font-size="7" fill="#FF9900" text-anchor="middle" opacity="0.6">COST: OPTIMIZED</text>
  </g>

  <!-- ══ DATABASE CAT - MySQL Keeper ══ -->
  <g>
    <rect x="690" y="55" width="195" height="155" rx="8" fill="rgba(0,117,143,0.06)" stroke="#00758F" stroke-width="1.2"/>
    <!-- Cat with glasses -->
    <rect x="755" y="100" width="30" height="22" rx="4" fill="#00758F" opacity="0.9"/>
    <rect x="758" y="82" width="24" height="22" rx="4" fill="#00758F" opacity="0.9"/>
    <polygon points="760,82 756,74 763,82" fill="#00758F"/>
    <polygon points="777,82 781,74 774,82" fill="#00758F"/>
    <!-- Glasses -->
    <rect x="760" y="86" width="8" height="7" rx="3" fill="none" stroke="#00f5ff" stroke-width="1.2"/>
    <rect x="771" y="86" width="8" height="7" rx="3" fill="none" stroke="#00f5ff" stroke-width="1.2"/>
    <line x1="768" y1="89" x2="771" y2="89" stroke="#00f5ff" stroke-width="0.8"/>
    <!-- Eyes through glasses -->
    <rect x="762" y="88" width="3" height="3" rx="1" fill="#00f5ff" opacity="0.8"><animate attributeName="height" values="3;0.5;3" dur="5s" repeatCount="indefinite"/></rect>
    <rect x="773" y="88" width="3" height="3" rx="1" fill="#00f5ff" opacity="0.8"><animate attributeName="height" values="3;0.5;3" dur="5s" repeatCount="indefinite" begin="0.1s"/></rect>
    <rect x="769" y="97" width="3" height="2" rx="1" fill="#aaddff"/>
    <!-- Tail - slow scholarly -->
    <path d="M 755 118 Q 740 112 745 100" fill="none" stroke="#00758F" stroke-width="3" stroke-linecap="round">
      <animate attributeName="d" values="M 755 118 Q 740 112 745 100;M 755 118 Q 738 120 740 108;M 755 118 Q 740 112 745 100" dur="2.5s" repeatCount="indefinite"/>
    </path>
    <!-- Server rack / DB stack -->
    <rect x="735" y="122" width="70" height="40" rx="3" fill="rgba(0,117,143,0.15)" stroke="#00758F" stroke-width="1"/>
    <ellipse cx="770" cy="127" rx="28" ry="6" fill="rgba(0,117,143,0.4)" stroke="#00758F" stroke-width="0.8"/>
    <rect x="742" y="127" width="56" height="18" fill="rgba(0,117,143,0.2)"/>
    <ellipse cx="770" cy="145" rx="28" ry="6" fill="rgba(0,117,143,0.4)" stroke="#00758F" stroke-width="0.8"/>
    <circle cx="790" cy="130" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="1.3s" repeatCount="indefinite"/></circle>
    <circle cx="790" cy="145" r="2" fill="#00ff88"><animate attributeName="opacity" values="1;0.3;1" dur="0.9s" repeatCount="indefinite"/></circle>
    <!-- Label -->
    <text x="787" y="83" font-family="'Courier New', monospace" font-size="8" fill="#00758F" text-anchor="middle">🐈 DB CAT</text>
    <text x="787" y="175" font-family="'Courier New', monospace" font-size="8" fill="#00758F" text-anchor="middle">MYSQL KEEPER</text>
    <text x="787" y="188" font-family="'Courier New', monospace" font-size="7" fill="#00758F" text-anchor="middle" opacity="0.6">RECORDS: 1.2M</text>
    <text x="787" y="200" font-family="'Courier New', monospace" font-size="7" fill="#00758F" text-anchor="middle" opacity="0.6">INTEGRITY: 100%</text>
  </g>
</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--              DYNAMIC METRICS + ACHIEVEMENT HALL              -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="metBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818"/>
      <stop offset="100%" style="stop-color:#020e08"/>
    </linearGradient>
    <filter id="metGlow"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <filter id="metGlow2"><feGaussianBlur stdDeviation="6" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>

  <rect width="900" height="280" fill="url(#metBg)"/>

  <!-- METRICS section header -->
  <text x="225" y="25" font-family="'Courier New', monospace" font-size="11" fill="#00f5ff" text-anchor="middle" letter-spacing="4">◈ LIVE METRICS ◈</text>
  <line x1="30" y1="35" x2="420" y2="35" stroke="#00f5ff" stroke-width="0.5" opacity="0.4"/>

  <!-- ACHIEVEMENTS header -->
  <text x="675" y="25" font-family="'Courier New', monospace" font-size="11" fill="#ffd700" text-anchor="middle" letter-spacing="4">◈ ACHIEVEMENT HALL ◈</text>
  <line x1="480" y1="35" x2="870" y2="35" stroke="#ffd700" stroke-width="0.5" opacity="0.4"/>

  <!-- ══ METRICS ══ -->
  <!-- Projects Deployed -->
  <rect x="30" y="50" width="185" height="90" rx="6" fill="rgba(0,245,255,0.05)" stroke="#00f5ff" stroke-width="1.2" filter="url(#metGlow)"/>
  <text x="122" y="76" font-family="'Courier New', monospace" font-size="10" fill="#00f5ff" text-anchor="middle" opacity="0.7" letter-spacing="1">PROJECTS DEPLOYED</text>
  <text x="122" y="118" font-family="'Courier New', monospace" font-size="36" fill="#00f5ff" text-anchor="middle" font-weight="bold" filter="url(#metGlow2)">12+</text>
  <text x="122" y="134" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.7">↑ PRODUCTION READY</text>
  <!-- Pulse -->
  <rect x="30" y="140" width="185" height="2" rx="1" fill="rgba(0,245,255,0.1)"/>
  <rect x="30" y="140" width="140" height="2" rx="1" fill="#00f5ff" opacity="0.5"><animate attributeName="width" values="140;185;100;160;140" dur="3s" repeatCount="indefinite"/></rect>

  <!-- API Requests -->
  <rect x="230" y="50" width="185" height="90" rx="6" fill="rgba(255,0,200,0.05)" stroke="#ff00c8" stroke-width="1.2" filter="url(#metGlow)"/>
  <text x="322" y="76" font-family="'Courier New', monospace" font-size="10" fill="#ff00c8" text-anchor="middle" opacity="0.7" letter-spacing="1">API REQ PROCESSED</text>
  <text x="322" y="118" font-family="'Courier New', monospace" font-size="36" fill="#ff00c8" text-anchor="middle" font-weight="bold" filter="url(#metGlow2)">2M+</text>
  <text x="322" y="134" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.7">↑ 847 req/s PEAK</text>
  <rect x="230" y="140" width="185" height="2" rx="1" fill="rgba(255,0,200,0.1)"/>
  <rect x="230" y="140" width="160" height="2" rx="1" fill="#ff00c8" opacity="0.5"><animate attributeName="width" values="160;185;130;170;160" dur="2.5s" repeatCount="indefinite"/></rect>

  <!-- Auth Tokens -->
  <rect x="30" y="165" width="185" height="90" rx="6" fill="rgba(255,215,0,0.05)" stroke="#ffd700" stroke-width="1.2" filter="url(#metGlow)"/>
  <text x="122" y="191" font-family="'Courier New', monospace" font-size="9" fill="#ffd700" text-anchor="middle" opacity="0.7" letter-spacing="1">AUTH TOKENS GEN</text>
  <text x="122" y="233" font-family="'Courier New', monospace" font-size="36" fill="#ffd700" text-anchor="middle" font-weight="bold" filter="url(#metGlow2)">500K</text>
  <text x="122" y="249" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.7">↑ JWT + RBAC</text>
  <rect x="30" y="255" width="185" height="2" rx="1" fill="rgba(255,215,0,0.1)"/>
  <rect x="30" y="255" width="120" height="2" rx="1" fill="#ffd700" opacity="0.5"><animate attributeName="width" values="120;185;90;150;120" dur="4s" repeatCount="indefinite"/></rect>

  <!-- Cloud Deployments -->
  <rect x="230" y="165" width="185" height="90" rx="6" fill="rgba(0,255,136,0.05)" stroke="#00ff88" stroke-width="1.2" filter="url(#metGlow)"/>
  <text x="322" y="191" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" text-anchor="middle" opacity="0.7" letter-spacing="1">CLOUD DEPLOYMENTS</text>
  <text x="322" y="233" font-family="'Courier New', monospace" font-size="36" fill="#00ff88" text-anchor="middle" font-weight="bold" filter="url(#metGlow2)">30+</text>
  <text x="322" y="249" font-family="'Courier New', monospace" font-size="8" fill="#00ff88" text-anchor="middle" opacity="0.7">↑ AWS MULTI-REGION</text>
  <rect x="230" y="255" width="185" height="2" rx="1" fill="rgba(0,255,136,0.1)"/>
  <rect x="230" y="255" width="150" height="2" rx="1" fill="#00ff88" opacity="0.5"><animate attributeName="width" values="150;185;110;165;150" dur="3.5s" repeatCount="indefinite"/></rect>

  <!-- Vertical divider -->
  <line x1="455" y1="40" x2="455" y2="270" stroke="#00f5ff" stroke-width="0.5" stroke-dasharray="4,4" opacity="0.2"/>

  <!-- ══ ACHIEVEMENTS ══ -->
  <!-- Hackathon Winner Card -->
  <g>
    <rect x="480" y="55" width="380" height="95" rx="8" fill="rgba(255,215,0,0.06)" stroke="#ffd700" stroke-width="1.5" filter="url(#metGlow)">
      <animate attributeName="stroke-width" values="1.5;2.5;1.5" dur="3s" repeatCount="indefinite"/>
    </rect>
    <!-- Golden glow on corners -->
    <line x1="480" y1="63" x2="490" y2="55" stroke="#ffd700" stroke-width="1.5"/>
    <line x1="852" y1="55" x2="860" y2="63" stroke="#ffd700" stroke-width="1.5"/>
    <line x1="480" y1="142" x2="490" y2="150" stroke="#ffd700" stroke-width="1.5"/>
    <line x1="852" y1="150" x2="860" y2="142" stroke="#ffd700" stroke-width="1.5"/>
    <!-- Trophy icon -->
    <text x="510" y="102" font-family="'Courier New', monospace" font-size="35" fill="#ffd700" filter="url(#metGlow2)">🏆</text>
    <!-- Content -->
    <text x="558" y="80" font-family="'Courier New', monospace" font-size="15" fill="#ffd700" font-weight="bold" filter="url(#metGlow)">HACKATHON WINNER</text>
    <text x="558" y="100" font-family="'Courier New', monospace" font-size="13" fill="#ffd700" opacity="0.9">CATCH-26  ·  2026</text>
    <text x="558" y="118" font-family="'Courier New', monospace" font-size="9" fill="#ffd700" opacity="0.6">AI-POWERED FRAUD DETECTION SYSTEM</text>
    <text x="558" y="134" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" opacity="0.7">◉ 1ST PLACE  ·  NATIONAL LEVEL</text>
    <!-- Stars -->
    <text x="840" y="80" font-family="'Courier New', monospace" font-size="14" fill="#ffd700" filter="url(#metGlow2)">★</text>
    <text x="828" y="98" font-family="'Courier New', monospace" font-size="10" fill="#ffd700" opacity="0.6" filter="url(#metGlow)">★</text>
    <text x="845" y="112" font-family="'Courier New', monospace" font-size="8" fill="#ffd700" opacity="0.4">★</text>
    <!-- Animated pulse ring -->
    <circle cx="510" cy="102" r="25" fill="none" stroke="#ffd700" stroke-width="1" opacity="0.3">
      <animate attributeName="r" values="25;35;25" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Honourable Mention Card -->
  <g>
    <rect x="480" y="170" width="380" height="85" rx="8" fill="rgba(192,192,192,0.06)" stroke="#c0c0c0" stroke-width="1.2" filter="url(#metGlow)">
      <animate attributeName="stroke-opacity" values="0.8;1;0.8" dur="4s" repeatCount="indefinite"/>
    </rect>
    <line x1="480" y1="178" x2="490" y2="170" stroke="#c0c0c0" stroke-width="1.2"/>
    <line x1="852" y1="170" x2="860" y2="178" stroke="#c0c0c0" stroke-width="1.2"/>
    <!-- Medal icon -->
    <text x="510" y="222" font-family="'Courier New', monospace" font-size="32" fill="#c0c0c0" filter="url(#metGlow)">🏅</text>
    <!-- Content -->
    <text x="558" y="194" font-family="'Courier New', monospace" font-size="13" fill="#c0c0c0" font-weight="bold">HONOURABLE MENTION</text>
    <text x="558" y="212" font-family="'Courier New', monospace" font-size="12" fill="#c0c0c0" opacity="0.9">DAKSHA 26  ·  2026</text>
    <text x="558" y="228" font-family="'Courier New', monospace" font-size="9" fill="#c0c0c0" opacity="0.6">IAM BACKEND SYSTEM  ·  SECURITY TRACK</text>
    <text x="558" y="244" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" opacity="0.7">◉ RECOGNISED FOR INNOVATION</text>
  </g>

</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                    ACTIVITY RADAR                            -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="320" viewBox="0 0 900 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="radarBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818"/>
      <stop offset="100%" style="stop-color:#020e18"/>
    </linearGradient>
    <filter id="radarGlow"><feGaussianBlur stdDeviation="4" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <!-- Radar sweep gradient -->
    <radialGradient id="sweepGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0.4"/>
      <stop offset="70%" style="stop-color:#00f5ff;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </radialGradient>
  </defs>

  <rect width="900" height="320" fill="url(#radarBg)"/>

  <text x="450" y="28" font-family="'Courier New', monospace" font-size="12" fill="#00f5ff" text-anchor="middle" letter-spacing="6">◈ ACTIVITY RADAR  ·  SKILL SPECTRUM ◈</text>
  <line x1="50" y1="38" x2="850" y2="38" stroke="#00f5ff" stroke-width="0.5" opacity="0.3"/>

  <!-- ══ RADAR CHART ══ -->
  <!-- Radar center: 230, 185 -->

  <!-- Background rings -->
  <polygon points="230,95 311,140 311,230 230,275 149,230 149,140" fill="none" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>
  <polygon points="230,118 296,153 296,217 230,252 164,217 164,153" fill="none" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>
  <polygon points="230,140 280,165 280,205 230,230 180,205 180,165" fill="none" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>
  <polygon points="230,162 264,178 264,192 230,208 196,192 196,178" fill="none" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>

  <!-- Axis lines -->
  <line x1="230" y1="95" x2="230" y2="275" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>
  <line x1="149" y1="140" x2="311" y2="230" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>
  <line x1="311" y1="140" x2="149" y2="230" stroke="rgba(0,245,255,0.1)" stroke-width="1"/>

  <!-- Skill areas: Backend(top), Security(upper-right), AI(lower-right), Cloud(bottom), Systems(lower-left), DB(upper-left) -->
  <!-- Data polygon - skill values -->
  <polygon points="230,102 303,148 298,222 230,268 162,218 162,148"
           fill="rgba(0,245,255,0.15)"
           stroke="#00f5ff"
           stroke-width="2"
           filter="url(#radarGlow)">
    <animate attributeName="points"
             values="230,102 303,148 298,222 230,268 162,218 162,148;
                     230,98 307,145 302,225 230,272 158,220 158,145;
                     230,102 303,148 298,222 230,268 162,218 162,148"
             dur="4s" repeatCount="indefinite"/>
  </polygon>

  <!-- Skill dots -->
  <circle cx="230" cy="102" r="5" fill="#00f5ff" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="2s" repeatCount="indefinite"/></circle>
  <circle cx="303" cy="148" r="5" fill="#ff00c8" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="2.3s" repeatCount="indefinite"/></circle>
  <circle cx="298" cy="222" r="5" fill="#ffd700" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="1.8s" repeatCount="indefinite"/></circle>
  <circle cx="230" cy="268" r="5" fill="#FF9900" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="162" cy="218" r="5" fill="#bf00ff" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="2.1s" repeatCount="indefinite"/></circle>
  <circle cx="162" cy="148" r="5" fill="#00ff88" filter="url(#radarGlow)"><animate attributeName="r" values="5;7;5" dur="1.6s" repeatCount="indefinite"/></circle>

  <!-- Radar sweep -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="0,230,185; 360,230,185" dur="4s" repeatCount="indefinite"/>
    <line x1="230" y1="185" x2="230" y2="95" stroke="#00f5ff" stroke-width="1.5" opacity="0.8" stroke-linecap="round"/>
    <path d="M 230 185 L 230 95 A 90 90 0 0 1 311 230 Z" fill="url(#sweepGrad)" opacity="0.3"/>
  </g>

  <!-- Center dot -->
  <circle cx="230" cy="185" r="4" fill="#00f5ff" filter="url(#radarGlow)"/>
  <circle cx="230" cy="185" r="8" fill="none" stroke="#00f5ff" stroke-width="0.8" opacity="0.5"/>

  <!-- Skill Labels -->
  <text x="230" y="85" font-family="'Courier New', monospace" font-size="9" fill="#00f5ff" text-anchor="middle" font-weight="bold">BACKEND</text>
  <text x="325" y="145" font-family="'Courier New', monospace" font-size="9" fill="#ff00c8" font-weight="bold">SECURITY</text>
  <text x="320" y="235" font-family="'Courier New', monospace" font-size="9" fill="#ffd700" font-weight="bold">AI / ML</text>
  <text x="230" y="293" font-family="'Courier New', monospace" font-size="9" fill="#FF9900" text-anchor="middle" font-weight="bold">CLOUD</text>
  <text x="90" y="235" font-family="'Courier New', monospace" font-size="9" fill="#bf00ff" font-weight="bold">SYSTEMS</text>
  <text x="95" y="145" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" text-anchor="end" font-weight="bold">DATABASE</text>

  <!-- Percentage labels -->
  <text x="230" y="97" font-family="'Courier New', monospace" font-size="7" fill="#00f5ff" text-anchor="middle" opacity="0.6">95%</text>
  <text x="310" y="155" font-family="'Courier New', monospace" font-size="7" fill="#ff00c8" opacity="0.6">90%</text>
  <text x="305" y="230" font-family="'Courier New', monospace" font-size="7" fill="#ffd700" opacity="0.6">85%</text>
  <text x="230" y="280" font-family="'Courier New', monospace" font-size="7" fill="#FF9900" text-anchor="middle" opacity="0.6">88%</text>
  <text x="152" y="228" font-family="'Courier New', monospace" font-size="7" fill="#bf00ff" text-anchor="end" opacity="0.6">85%</text>
  <text x="156" y="145" font-family="'Courier New', monospace" font-size="7" fill="#00ff88" text-anchor="end" opacity="0.6">87%</text>

  <!-- ══ SIDE PANEL: Skills Bar Chart ══ -->
  <!-- Java -->
  <text x="490" y="75" font-family="'Courier New', monospace" font-size="9" fill="#FF6B35" opacity="0.9">JAVA</text>
  <rect x="560" y="62" width="290" height="14" rx="2" fill="rgba(255,107,53,0.1)"/>
  <rect x="560" y="62" width="275" height="14" rx="2" fill="#FF6B35" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="73" font-family="'Courier New', monospace" font-size="8" fill="#FF6B35" text-anchor="end">95%</text>

  <!-- Spring Boot -->
  <text x="490" y="105" font-family="'Courier New', monospace" font-size="9" fill="#6DB33F" opacity="0.9">SPRING BOOT</text>
  <rect x="560" y="92" width="290" height="14" rx="2" fill="rgba(109,179,63,0.1)"/>
  <rect x="560" y="92" width="261" height="14" rx="2" fill="#6DB33F" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="103" font-family="'Courier New', monospace" font-size="8" fill="#6DB33F" text-anchor="end">90%</text>

  <!-- AWS -->
  <text x="490" y="135" font-family="'Courier New', monospace" font-size="9" fill="#FF9900" opacity="0.9">AWS CLOUD</text>
  <rect x="560" y="122" width="290" height="14" rx="2" fill="rgba(255,153,0,0.1)"/>
  <rect x="560" y="122" width="250" height="14" rx="2" fill="#FF9900" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="133" font-family="'Courier New', monospace" font-size="8" fill="#FF9900" text-anchor="end">86%</text>

  <!-- MySQL -->
  <text x="490" y="165" font-family="'Courier New', monospace" font-size="9" fill="#00758F" opacity="0.9">MYSQL</text>
  <rect x="560" y="152" width="290" height="14" rx="2" fill="rgba(0,117,143,0.1)"/>
  <rect x="560" y="152" width="246" height="14" rx="2" fill="#00758F" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="163" font-family="'Courier New', monospace" font-size="8" fill="#00758F" text-anchor="end">85%</text>

  <!-- Redis -->
  <text x="490" y="195" font-family="'Courier New', monospace" font-size="9" fill="#DC382D" opacity="0.9">REDIS</text>
  <rect x="560" y="182" width="290" height="14" rx="2" fill="rgba(220,56,45,0.1)"/>
  <rect x="560" y="182" width="240" height="14" rx="2" fill="#DC382D" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="193" font-family="'Courier New', monospace" font-size="8" fill="#DC382D" text-anchor="end">83%</text>

  <!-- Docker -->
  <text x="490" y="225" font-family="'Courier New', monospace" font-size="9" fill="#2496ED" opacity="0.9">DOCKER</text>
  <rect x="560" y="212" width="290" height="14" rx="2" fill="rgba(36,150,237,0.1)"/>
  <rect x="560" y="212" width="232" height="14" rx="2" fill="#2496ED" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="223" font-family="'Courier New', monospace" font-size="8" fill="#2496ED" text-anchor="end">80%</text>

  <!-- JWT Security -->
  <text x="490" y="255" font-family="'Courier New', monospace" font-size="9" fill="#bf00ff" opacity="0.9">JWT / IAM</text>
  <rect x="560" y="242" width="290" height="14" rx="2" fill="rgba(191,0,255,0.1)"/>
  <rect x="560" y="242" width="255" height="14" rx="2" fill="#bf00ff" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="253" font-family="'Courier New', monospace" font-size="8" fill="#bf00ff" text-anchor="end">88%</text>

  <!-- System Design -->
  <text x="490" y="285" font-family="'Courier New', monospace" font-size="9" fill="#00f5ff" opacity="0.9">SYS DESIGN</text>
  <rect x="560" y="272" width="290" height="14" rx="2" fill="rgba(0,245,255,0.1)"/>
  <rect x="560" y="272" width="268" height="14" rx="2" fill="#00f5ff" opacity="0.8" filter="url(#radarGlow)"/>
  <text x="858" y="283" font-family="'Courier New', monospace" font-size="8" fill="#00f5ff" text-anchor="end">92%</text>

</svg>

<br/><br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                  SOCIAL LINKS + VISITOR                      -->
<!-- ████████████████████████████████████████████████████████████ -->

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sanjay_Varadharajan-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanjay-varadharajan)
[![GitHub](https://img.shields.io/badge/GitHub-sanjayvrd-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sanjayvrd)
[![Email](https://img.shields.io/badge/Email-Contact-%23EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanjay@example.com)

![Profile Views](https://komarev.com/ghpvc/?username=sanjayvrd&color=00f5ff&style=for-the-badge&label=SYSTEM+ACCESSES)

<br/>

<!-- ████████████████████████████████████████████████████████████ -->
<!--                    FOOTER - SLEEPING CAT                     -->
<!-- ████████████████████████████████████████████████████████████ -->

<svg width="900" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#020818"/>
      <stop offset="100%" style="stop-color:#000510"/>
    </linearGradient>
    <filter id="footGlow"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <filter id="footGlow2"><feGaussianBlur stdDeviation="6" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <radialGradient id="starGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </radialGradient>
  </defs>

  <rect width="900" height="220" fill="url(#footBg)"/>

  <!-- Starfield -->
  <!-- Stars row 1 -->
  <circle cx="45" cy="25" r="1.2" fill="#ffffff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.1s" repeatCount="indefinite"/></circle>
  <circle cx="120" cy="15" r="0.8" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="3.2s" repeatCount="indefinite"/></circle>
  <circle cx="200" cy="30" r="1.5" fill="#ffffff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.8s" repeatCount="indefinite"/></circle>
  <circle cx="310" cy="10" r="0.9" fill="#ffffff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="2.7s" repeatCount="indefinite"/></circle>
  <circle cx="380" cy="22" r="1.3" fill="#ff00c8" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.5s" repeatCount="indefinite"/></circle>
  <circle cx="450" cy="8" r="1.0" fill="#ffffff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.3s" repeatCount="indefinite"/></circle>
  <circle cx="520" cy="28" r="0.8" fill="#00f5ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.9s" repeatCount="indefinite"/></circle>
  <circle cx="610" cy="14" r="1.4" fill="#ffffff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.8s" repeatCount="indefinite"/></circle>
  <circle cx="690" cy="25" r="0.9" fill="#ffd700" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.1s" repeatCount="indefinite"/></circle>
  <circle cx="760" cy="10" r="1.2" fill="#ffffff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.4s" repeatCount="indefinite"/></circle>
  <circle cx="840" cy="20" r="1.0" fill="#00f5ff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="1.7s" repeatCount="indefinite"/></circle>
  <circle cx="875" cy="32" r="0.7" fill="#ffffff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="3.0s" repeatCount="indefinite"/></circle>
  <!-- Stars row 2 -->
  <circle cx="80" cy="48" r="0.7" fill="#ffffff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="4.1s" repeatCount="indefinite"/></circle>
  <circle cx="155" cy="55" r="1.1" fill="#ff00c8" opacity="0.4"><animate attributeName="opacity" values="0.4;0.1;0.4" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="260" cy="42" r="0.9" fill="#ffffff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="3.3s" repeatCount="indefinite"/></circle>
  <circle cx="340" cy="58" r="0.6" fill="#00f5ff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.0s" repeatCount="indefinite"/></circle>
  <circle cx="480" cy="45" r="1.2" fill="#ffffff" opacity="0.8"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="1.5s" repeatCount="indefinite"/></circle>
  <circle cx="555" cy="52" r="0.8" fill="#ffd700" opacity="0.4"><animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.8s" repeatCount="indefinite"/></circle>
  <circle cx="645" cy="44" r="1.0" fill="#ffffff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.2s" repeatCount="indefinite"/></circle>
  <circle cx="720" cy="56" r="0.7" fill="#00f5ff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="1.6s" repeatCount="indefinite"/></circle>
  <circle cx="810" cy="42" r="1.3" fill="#ffffff" opacity="0.9"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="3.6s" repeatCount="indefinite"/></circle>
  <circle cx="860" cy="55" r="0.6" fill="#ff00c8" opacity="0.4"><animate attributeName="opacity" values="0.4;0.1;0.4" dur="2.9s" repeatCount="indefinite"/></circle>

  <!-- Server rack 1 -->
  <rect x="480" y="130" width="130" height="55" rx="4" fill="rgba(0,245,255,0.08)" stroke="#00f5ff" stroke-width="1.2"/>
  <rect x="484" y="134" width="122" height="10" rx="2" fill="rgba(0,245,255,0.2)"/>
  <rect x="484" y="147" width="122" height="10" rx="2" fill="rgba(0,245,255,0.15)"/>
  <rect x="484" y="160" width="122" height="10" rx="2" fill="rgba(0,245,255,0.18)"/>
  <circle cx="598" cy="139" r="2.5" fill="#00ff88"><animate attributeName="opacity" values="1;0.2;1" dur="1.3s" repeatCount="indefinite"/></circle>
  <circle cx="598" cy="152" r="2.5" fill="#00ff88"><animate attributeName="opacity" values="1;0.2;1" dur="0.9s" repeatCount="indefinite"/></circle>
  <circle cx="598" cy="165" r="2.5" fill="#ffd700"><animate attributeName="opacity" values="1;0.2;1" dur="1.8s" repeatCount="indefinite"/></circle>

  <!-- Server rack 2 -->
  <rect x="290" y="140" width="120" height="45" rx="4" fill="rgba(191,0,255,0.08)" stroke="#bf00ff" stroke-width="1.2"/>
  <rect x="294" y="144" width="112" height="9" rx="2" fill="rgba(191,0,255,0.2)"/>
  <rect x="294" y="156" width="112" height="9" rx="2" fill="rgba(191,0,255,0.15)"/>
  <circle cx="397" cy="149" r="2.5" fill="#00ff88"><animate attributeName="opacity" values="1;0.2;1" dur="1.1s" repeatCount="indefinite"/></circle>
  <circle cx="397" cy="161" r="2.5" fill="#00ff88"><animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite"/></circle>

  <!-- ══ BIG SLEEPING CAT on server ══ -->
  <g>
    <!-- Cat body - curled up, sleeping -->
    <!-- Main body curl -->
    <ellipse cx="430" cy="148" rx="60" ry="32" fill="#0a0a20" stroke="#00f5ff" stroke-width="1.2" filter="url(#footGlow)"/>
    <!-- Inner body curve -->
    <ellipse cx="435" cy="148" rx="50" ry="25" fill="#0d0d28" stroke="#00f5ff" stroke-width="0.6" opacity="0.5"/>
    <!-- Head -->
    <ellipse cx="370" cy="145" rx="28" ry="25" fill="#0a0a20" stroke="#00f5ff" stroke-width="1.2" filter="url(#footGlow)"/>
    <!-- Ears -->
    <polygon points="358,122 353,112 365,122" fill="#0a0a20" stroke="#00f5ff" stroke-width="1"/>
    <polygon points="375,120 380,110 385,120" fill="#0a0a20" stroke="#00f5ff" stroke-width="1"/>
    <!-- Ear inner pink -->
    <polygon points="360,122 355,115 365,122" fill="#ff00c8" opacity="0.3"/>
    <polygon points="377,120 381,113 385,120" fill="#ff00c8" opacity="0.3"/>
    <!-- Sleeping eyes - closed Z lines -->
    <path d="M 358 143 Q 363 140 368 143" fill="none" stroke="#00f5ff" stroke-width="1.5" stroke-linecap="round"/>
    <path d="M 372 143 Q 377 140 382 143" fill="none" stroke="#00f5ff" stroke-width="1.5" stroke-linecap="round"/>
    <!-- Nose -->
    <ellipse cx="370" cy="150" rx="3" ry="2" fill="#ff00c8" opacity="0.8"/>
    <!-- Whiskers -->
    <line x1="370" y1="150" x2="350" y2="146" stroke="#00f5ff" stroke-width="0.6" opacity="0.5"/>
    <line x1="370" y1="151" x2="350" y2="153" stroke="#00f5ff" stroke-width="0.6" opacity="0.5"/>
    <line x1="370" y1="150" x2="390" y2="146" stroke="#00f5ff" stroke-width="0.6" opacity="0.5"/>
    <line x1="370" y1="151" x2="390" y2="153" stroke="#00f5ff" stroke-width="0.6" opacity="0.5"/>
    <!-- Tail wrapped around - thick and glowing -->
    <path d="M 490 148 Q 520 170 510 185 Q 500 200 470 190 Q 450 182 445 165" fill="none" stroke="#00f5ff" stroke-width="4" stroke-linecap="round" filter="url(#footGlow)">
      <animate attributeName="d" values="M 490 148 Q 520 170 510 185 Q 500 200 470 190 Q 450 182 445 165;M 490 148 Q 522 172 514 188 Q 505 203 474 193 Q 452 184 447 167;M 490 148 Q 520 170 510 185 Q 500 200 470 190 Q 450 182 445 165" dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Tail tip -->
    <circle cx="445" cy="165" r="5" fill="#00f5ff" opacity="0.6" filter="url(#footGlow)">
      <animate attributeName="cy" values="165;167;165" dur="3s" repeatCount="indefinite"/>
    </circle>
    <!-- Paws -->
    <ellipse cx="395" cy="168" rx="16" ry="8" fill="#0a0a20" stroke="#00f5ff" stroke-width="1" opacity="0.9"/>
    <ellipse cx="418" cy="168" rx="14" ry="7" fill="#0a0a20" stroke="#00f5ff" stroke-width="1" opacity="0.8"/>
    <!-- ZZZ sleep symbols -->
    <text x="345" y="125" font-family="'Courier New', monospace" font-size="12" fill="#00f5ff" opacity="0.8" filter="url(#footGlow)">
      z
      <animate attributeName="opacity" values="0.8;0.1;0.8" dur="3s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; -5,-15" dur="3s" repeatCount="indefinite" additive="sum"/>
    </text>
    <text x="332" y="112" font-family="'Courier New', monospace" font-size="10" fill="#00f5ff" opacity="0.6" filter="url(#footGlow)">
      z
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="3s" repeatCount="indefinite" begin="0.5s"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; -8,-20" dur="3s" repeatCount="indefinite" begin="0.5s" additive="sum"/>
    </text>
    <text x="318" y="100" font-family="'Courier New', monospace" font-size="8" fill="#00f5ff" opacity="0.4" filter="url(#footGlow)">
      z
      <animate attributeName="opacity" values="0.4;0;0.4" dur="3s" repeatCount="indefinite" begin="1s"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; -10,-25" dur="3s" repeatCount="indefinite" begin="1s" additive="sum"/>
    </text>
    <!-- Gentle breathing animation - scale -->
    <animateTransform attributeName="transform" type="scale" values="1,1; 1.01,1.01; 1,1" dur="4s" repeatCount="indefinite" additive="sum"/>
  </g>

  <!-- Ground line -->
  <line x1="50" y1="185" x2="850" y2="185" stroke="#00f5ff" stroke-width="0.5" opacity="0.2"/>

  <!-- Terminal status messages -->
  <rect x="30" y="193" width="840" height="22" rx="3" fill="rgba(0,245,255,0.04)" stroke="#00f5ff" stroke-width="0.5" opacity="0.5"/>
  <text x="45" y="208" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" opacity="0.9">◉ SYSTEM STABLE.</text>
  <text x="220" y="208" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" opacity="0.7">  ·  ALL SERVICES OPERATIONAL.</text>
  <text x="510" y="208" font-family="'Courier New', monospace" font-size="9" fill="#00f5ff" opacity="0.5">  ·  UPTIME: 99.99%  ·  SANJAY VARADHARAJAN © 2026</text>
  <!-- Blinking cursor -->
  <rect x="836" y="199" width="6" height="12" rx="1" fill="#00f5ff" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0;0.8" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>
