<svg width="1000" height="320" viewBox="0 0 1000 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="og" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#FF6B00"/>
      <stop offset="100%" stop-color="#FFB300"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#1d1d1d" stroke-width="1"/>
      <animateTransform attributeName="patternTransform" type="translate" from="0 0" to="40 40" dur="5s" repeatCount="indefinite"/>
    </pattern>
    <filter id="blur"><feGaussianBlur stdDeviation="45"/></filter>
  </defs>

  <rect width="1000" height="320" fill="#0a0a0a"/>
  <rect width="1000" height="320" fill="url(#grid)"/>

  <circle cx="820" cy="160" r="110" fill="#FF6B00" opacity="0.35" filter="url(#blur)">
    <animate attributeName="opacity" values="0.2;0.45;0.2" dur="4s" repeatCount="indefinite"/>
  </circle>

  <g transform="translate(820 160)">
    <circle r="95" fill="none" stroke="#FF6B00" stroke-width="2" stroke-dasharray="6 14">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite"/>
    </circle>
    <circle r="70" fill="none" stroke="#FFB300" stroke-width="1.5" stroke-dasharray="40 20" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="14s"
