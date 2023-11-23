<template>
  <footer class="footer">
    <div class="container-fluid">
      &copy; {{ year }},
        Mari&Jhon. Todos los derechos reservados.
      <div class="copyright">
        
        Este sitio utiliza recursos de <a
          href="https://www.creative-tim.com/?ref=pdf-vuejs"
          target="_blank"
          rel="noopener"
          >Creative-Tim</a
        >    
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
