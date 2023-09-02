<script setup lang="ts"></script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <div class="description">
    <p>Please can you make this exercise:</p>
    <ul>
      <li>Create 1 component with a text box and button</li>
      <li>
        Create 1 component with a list of names submitted by the first component
      </li>
    </ul>
    <img
      src="https://raw.githubusercontent.com/fabiomilheiro/React-basic-app/main/public/components.png"
    />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.description {
  text-align: left;
}
</style>
