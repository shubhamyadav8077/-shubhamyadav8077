
<svg width="100%" height="220" viewBox="0 0 600 220"
     xmlns="http://www.w3.org/2000/svg">

  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <path d="M300 0 V65" stroke="#00ff41" stroke-width="2"/>

  <g filter="url(#glow)" stroke="#00ff41"
     stroke-width="3" fill="none">
    <animateTransform attributeName="transform"
      type="translate" values="0 0;0 35;0 0"
      dur="3s" repeatCount="indefinite"/>

    <circle cx="300" cy="85" r="13" fill="#00ff41"/>
    <circle cx="300" cy="108" r="9" fill="#00ff41"/>

    <path d="M290 88 L265 72 L250 90
             M290 96 L260 100 L245 120
             M292 105 L270 130 L255 145
             M310 88 L335 72 L350 90
             M310 96 L340 100 L355 120
             M308 105 L330 130 L345 145"/>
  </g>

  <text x="300" y="195" text-anchor="middle"
    fill="#00ff41" font-size="18"
    font-family="monospace">
    SPIDER SECURITY SYSTEM
  </text>
</svg>
