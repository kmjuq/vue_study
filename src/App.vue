<template>
  <HelloWorld msg="Hello Vue 3 + Vite" />
  <Counter />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/Counter.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

/* ./src/index.css */

/*! @import */
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
