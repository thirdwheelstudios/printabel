<template>
  <nav>
    <router-link to="/" class="brand">Printabel</router-link>
    <ul>
      <li>
        <router-link to="/create">Create Labels</router-link>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  background: linear-gradient(to right, #303f9f 66%, #3f51b5);
}

.brand {
  font-size: 1.5em;
}

a {
  color: rgba(255, 255, 255, 0.85);
  padding: 0.25em 0.5em;
  margin: 0.25em;
  border-radius: 1.5em;
}

a:hover,
a.router-link-active {
  color: rgba(255, 255, 255, 0.9);
  background-color: rgba(255, 255, 255, 0.2);
}

ul {
  display: flex;
  list-style: none;
  padding-left: 0;
  text-transform: uppercase;
}
</style>
