<template>
  <nav>
    <router-link to="/" class="brand">Printabel</router-link>
  </nav>
</template>

<style scoped>
nav {
  padding: 1em;
  background: linear-gradient(to right, #303f9f, #3f51b5);
}

a {
  color: rgba(255, 255, 255, 0.75);
  text-decoration: none;
  padding: 0.25em 0.5em;
  border-radius: 1.5em;
}

a:hover {
  color: rgba(255, 255, 255, 0.9);
  background-color: rgba(255, 255, 255, 0.2);
}

.brand {
  font-weight: 700;
  font-size: 1.5em;
}
</style>
