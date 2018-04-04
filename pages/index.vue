<template>
  <div class="container home-page">
    <section class="intro">

    </section>
    <section class="featured-posts">
      <nuxt-link to="/posts/1">
        <article class="post-preview">
          <div class="card">

          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>

<script>

import Logo from '~/components/Logo.vue'
import UserTable from '~/components/UserTable.vue'

export default {
  components: {
    Logo,
    UserTable
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 55px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
