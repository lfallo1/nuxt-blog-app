<template>
  <div>
    <div class="container">
      <nuxt/>
    </div>
    <div class="footer text-center">
      <button type="button" class="btn btn-primary" @click="$router.push('/')">Home</button>
    </div>
  </div>
</template>

<style>

  .footer {
    margin-bottom: 20px;
  }

  html {
    font-family: "Open Sans", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  }
</style>
