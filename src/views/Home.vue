<template>
  <div class="content">
    <h1>Fuss-free Label Printing</h1>
    <p>
      Printabel enables you to create and print custom sheet labels without any
      of the hassle of installing additional software.
    </p>
    <button>
      <router-link to="/create">Create some labels!</router-link>
    </button>
  </div>
</template>

<style scoped>
div {
  text-align: center;
}

button {
  margin: 1em;
  background-color: #303f9f;
  border-radius: 3em;
  border-style: none;
  padding: 1em 0.5em;
  text-transform: uppercase;
  font-size: 1.1em;
  box-shadow: 0.2em 0.4em 0.8em #444;
}

button:hover {
  background-color: #3f51b5;
}

a {
  color: rgba(255, 255, 255, 0.85);
  padding: 1.5em;
}

a:hover {
  color: rgba(255, 255, 255, 0.9);
}
</style>
