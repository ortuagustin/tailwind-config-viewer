<template>
  <div id="app" class="font-sans" :class="{dark: darkMode}">
    <div class="border-b border-gray-900 p-4 text-gray-700 text-xl font-bold" style="backgroundColor: var(--bg-2); color: var(--fg)">
      Tailwind Config Viewer
      <input type="checkbox" v-model="darkMode">
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  data () {
    return {
      darkMode: false
    }
  }
}
</script>

<style>
html {
  --bg: theme('colors.gray.100');
  --bg-2: theme('colors.white');
  --fg: theme('colors.gray.800');
}
body {
  background-color: #fff !important;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.dark {
  --bg: theme('colors.gray.900');
  --bg-2: theme('colors.gray.800');
  --fg: theme('colors.gray.400');
}
</style>
