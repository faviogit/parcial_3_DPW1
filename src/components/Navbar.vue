<template>
  <nav>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/contador">Contador</router-link></li>
    </ul>
  </nav>
</template>

<script setup>

</script>

<style scoped>
nav {
  background-color: #c21919;
  padding: 1rem;
}
ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}
li {
  color: rgb(91, 67, 9);
}
a {
  color: rgb(166, 177, 190);
  text-decoration: none;
}
a.router-link-exact-active {
  font-weight: bold;
}
</style>
