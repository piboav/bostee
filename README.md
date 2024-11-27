<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1920 1080">
  <!-- Dark background with subtle texture -->
  <rect width="1920" height="1080" fill="#1A1A2E"/>
  
  <!-- Distant mountain silhouettes -->
  <path d="M0 540 L400 300 L800 540 L1200 250 L1600 540 L1920 400 V1080 H0 Z" fill="#14213D" opacity="0.7"/>
  
  <!-- Closer mountain layers with different depths -->
  <path d="M0 640 L300 450 L600 640 L900 350 L1200 640 L1500 300 L1920 640 V1080 H0 Z" fill="#283149" opacity="0.8"/>
  
  <!-- Mystical rune-like patterns -->
  <g opacity="0.3">
    <path d="M100 200 Q150 250, 200 200 Q250 150, 300 200" stroke="#4A4E69" stroke-width="2" fill="none"/>
    <path d="M1600 100 Q1650 150, 1700 100 Q1750 50, 1800 100" stroke="#4A4E69" stroke-width="2" fill="none"/>
    <path d="M500 50 Q550 100, 600 50 Q650 0, 700 50" stroke="#4A4E69" stroke-width="2" fill="none"/>
  </g>
  
  <!-- Faint magical sparkles -->
  <g fill="#FFD700" opacity="0.5">
    <circle cx="250" cy="150" r="3"/>
    <circle cx="750" cy="300" r="2"/>
    <circle cx="1300" cy="200" r="4"/>
    <circle cx="1700" cy="350" r="3"/>
  </g>
  
  <!-- Subtle vignette effect -->
  <radialGradient id="vignette" cx="50%" cy="50%" r="50%">
    <stop offset="70%" stop-color="#000" stop-opacity="0"/>
    <stop offset="100%" stop-color="#000" stop-opacity="0.3"/>
  </radialGradient>
  <rect width="1920" height="1080" fill="url(#vignette)"/>
</svg>
