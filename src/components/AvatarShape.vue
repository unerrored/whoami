<script setup lang="ts">
const isDark = useDark()
const logoColor = computed(() => (isDark.value ? '#fdfdfd' : '#303030'))
</script>

<template>
  <svg
    id="svg1" :stroke="logoColor" version="1.1" width="38.814801" height="38.857736"
    viewBox="0 0 458.14801 428.57736" sodipodi:docname="Doctor Wu avatar.svg"
    inkscape:version="1.3.2 (091e20e, 2023-11-25)" xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
    xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd" xmlns="http://www.w3.org/2000/svg"
    xmlns:svg="http://www.w3.org/2000/svg"
  >
    <defs
      id="defs1"
    >
      <filter
        id="mask-powermask-path-effect4_inverse"
        inkscape:label="filtermask-powermask-path-effect4"
        style="color-interpolation-filters:sRGB"
        height="100"
        width="100"
        x="-50"
        y="-50"
      >
        <feColorMatrix
          id="mask-powermask-path-effect4_primitive1"
          values="1"
          type="saturate"
          result="fbSourceGraphic"
        />
        <feColorMatrix
          id="mask-powermask-path-effect4_primitive2"
          values="-1 0 0 0 1 0 -1 0 0 1 0 0 -1 0 1 0 0 0 1 0 "
          in="fbSourceGraphic"
        />
      </filter>
      <clipPath
        id="clipPath4"
        clipPathUnits="userSpaceOnUse"
      >
        <circle
          id="circle4"
          style="opacity:0.838889;fill:#000000;fill-opacity:0.00120772;stroke:#000000;stroke-width:2.265"
          cx="228.52107"
          cy="247.67755"
          r="228.83249"
        />
      </clipPath>
    </defs>
    <sodipodi:namedview
      id="namedview1" pagecolor="#ffffff" bordercolor="#000000" borderopacity="0.25"
      inkscape:showpageshadow="2" inkscape:pageopacity="0.0" inkscape:pagecheckerboard="0" inkscape:deskcolor="#d1d1d1"
      inkscape:zoom="0.85652174" inkscape:cx="228.83249" inkscape:cy="199.64467" inkscape:window-width="1440"
      inkscape:window-height="847" inkscape:window-x="0" inkscape:window-y="855" inkscape:window-maximized="1"
      inkscape:current-layer="g1"
    />
    <g
      id="g1" inkscape:groupmode="layer" inkscape:label="Image"
      transform="translate(-0.85608899,-30.520181)"
    >
      >
      <path
        id="path1" style="fill:transparent" stroke-width="2"
        d="M 388.37639,1.2354662 C 353.04068,0.46010248 317.0434,26.638191 331.96398,57.211705 c 4.28453,8.779561 5.40171,6.93305 5.22053,-8.630286 -0.69542,-59.74173 85.64314,-53.800666 93.90663,6.461748 7.21256,52.597283 -61.42781,113.296233 -84.50543,74.728183 -17.50791,-29.26012 18.54863,-99.992475 50.7496,-99.555336 7.68448,0.104316 8.22855,-1.744299 1.3874,-4.720887 -17.58872,-7.652903 -44.19622,10.968191 -58.47378,40.925325 -17.3977,36.503628 -8.47369,73.554848 19.06829,79.174928 56.44373,11.5175 109.1135,-90.234288 67.14573,-129.717485 C 415.92944,5.9679478 402.20343,1.5388748 388.37639,1.2354662 Z M 493.79297,130.05648 c -0.33769,0.21981 -0.67726,0.44538 -1.02146,0.71005 -0.83698,1.52648 0.52854,0.0681 0.73188,-0.23302 0.10433,-0.1546 0.19313,-0.31802 0.28958,-0.47703 z m -162.1028,15.27023 c -7.23657,0.0321 -11.52311,4.04719 -11.52311,12.22442 0,4.56387 3.45866,4.82925 4.53869,0.34817 2.73324,-11.34029 16.79031,-7.59655 33.96908,9.04974 22.81666,22.10906 34.05929,28.38338 54.97238,30.67755 5.299,0.58131 9.93877,1.13069 10.30945,1.21997 8.43727,2.03266 24.74012,-5.6903 27.72708,-13.13459 5.07847,-12.65729 -14.51264,-32.96672 -31.79979,-32.96672 -4.50356,0 -0.29581,4.32043 6.08932,6.2534 15.71109,4.75609 26.34396,21.86821 18.29955,29.44933 -11.41769,10.7603 -41.18661,1.00319 -72.88492,-23.88955 -16.21221,-12.73154 -30.39352,-19.27295 -39.69773,-19.23172 z"
        clip-path="url(#clipPath4)"
      />
    </g>
  </svg>
</template>

<style scoped>
#path1 {
  stroke-dasharray: 3600;
  stroke-dashoffset: 3600;
  fill: transparent;
  animation: drawSignature 8s linear infinite;
}

@keyframes drawSignature {
  0% {
    stroke-dashoffset: 3600;
  }

  15% {
    /* fill: transparent; */
  }

  55%,
  75% {
    stroke-dashoffset: 0;
    /* fill: v-bind(logoColor); */
  }

  90%,
  100% {
    stroke-dashoffset: 3600;
    fill: transparent;
  }
}
</style>
