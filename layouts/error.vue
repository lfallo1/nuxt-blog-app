<template>
  <div class="card border-danger mb-3" style="max-width: 18rem;">
    <div class="card-header display-4">{{error.statusCode}}</div>
    <div class="card-body text-danger">
      <h5 class="card-title">{{error.message}}</h5>
      <nuxt-link class="card-link" to="/">Home</nuxt-link>
    </div>
  </div>
</template>

<style scoped>
  .card{
    margin: 30px auto;
  }
</style>

<script>
  export default {
    props: ['error']
  }
</script>
