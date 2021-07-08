<template>
  <div class="app-frame">
    <svg
      id="circle01"
      viewBox="0 0 100 100"
      preserveAspectRatio="slice"
      xmlns="http://www.w3.org/2000/svg"
    >
      <defs>
        <linearGradient x1="50%" y1=".779%" x2="50%" y2="100%" id="a">
          <stop stop-color="#0989B4" stop-opacity="0" offset="0%" />
          <stop stop-color="#53FFEE" offset="99.94%" />
        </linearGradient>
      </defs>

      <ellipse
        fill="url(#a)"
        transform="rotate(-135 50 50)"
        cx="50"
        cy="50"
        rx="50"
        ry="50"
        fill-rule="evenodd"
        opacity="1"
      />
    </svg>
    <svg
      id="circle02"
      viewBox="0 0 100 100"
      preserveAspectRatio="slice"
      xmlns="http://www.w3.org/2000/svg"
    >
      <defs>
        <linearGradient x1="50%" y1=".779%" x2="50%" y2="100%" id="a">
          <stop stop-color="#0989B4" stop-opacity="0" offset="0%" />
          <stop stop-color="#53FFEE" offset="99.94%" />
        </linearGradient>
      </defs>

      <ellipse
        fill="url(#a)"
        transform="rotate(45 50 50)"
        cx="50"
        cy="50"
        rx="50"
        ry="50"
        fill-rule="evenodd"
        opacity="1"
      />
    </svg>
    <slot />
  </div>
</template>

<script>
export default {
  name: "AppBkgrnd.vue",
  components: {},
};
</script>

<style>
.app-frame {
  background: rgb(27, 160, 173);
  height: 100vh;
  width: 100vw;
  z-index: 1;
}
#circle01 {
  height: 100vh;
  width: 100vh;
  position: fixed;
  z-index: 2;
  top: -45vh;
  left: -45vh;
}
#circle02 {
  height: 100vh;
  width: 100vh;
  position: fixed;
  z-index: 2;
  bottom: -45vh;
  right: -45vh;
}
</style>
