<template>

  <section class="jumbotron">
      <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
  </section>
  
</template>

<script>
export default {
  name: 'Jumbotron',
}
</script>

<style scoped>

.jumbotron {
  width: 100%;
  height: 400px;
}

.jumbotron img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 100% 0;
}

</style>