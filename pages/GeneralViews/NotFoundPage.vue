<template>
  <layout_auth class="not-found-page">
    <div class="centered">
      <h1><i class="not-found-icon nc-icon nc-puzzle-10"></i>404</h1>
      <p>No se encontró la página solicitada.</p>
    </div>
  </layout_auth>
</template>

<script>
export default {
  layout: 'auth'
};
</script>
<style lang="scss">
.not-found-page {
  .full-page > .content,
  .centered {
    min-height: calc(100vh - 160px);
  }
  .not-found-icon {
    margin-right: 10px;
  }
  .centered {
    h1,
    i {
      font-size: 50px;
    }
    p {
      font-size: 20px;
    }
    display: flex;
    padding-bottom: 150px;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: white;
  }
}
</style>
