<template>
  <div class="not-found-page centered">
    <h1>Ha ocurrido un error</h1>
    <NuxtLink to="/">Volver al inicio</NuxtLink>
  </div>
</template>

<script>
export default {
  name: 'error',
  props: ['error'],
  layout: false // Especifica que este layout no hereda de otros layouts
}
</script>

<style scoped>
.centered {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  text-align: center;
  background-color: #f8f9fa;
  color: #343a40;
}

h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: black;
}

a {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  color: #fff;
  background-color: #007bff;
  text-decoration: none;
  border-radius: 0.25rem;
  transition: background-color 0.3s ease;
}

a:hover {
  background-color: #0056b3;
}
</style>
