<template>
  <div class="col-md-12 featured-posts">
    <nuxt-link :to="'/posts/' + id">
      <div class="card post-preview" style="width: 18rem;">
        <div class="card-body">
          <h5 class="card-title display-4">{{title}}</h5>
          <p class="card-text">{{previewText}}</p>
          <a href="" class="card-link">Card link</a>
        </div>
      </div>
    </nuxt-link>
  </div>
</template>

<script>
  export default{
    props: {
      id: {type: String, required: true},
      title: {type: String, required: true},
      previewText: {type: String, required: true},
    }
  }
</script>

<style scoped>
  .post-preview{
    margin: 0px auto;
    margin-bottom: 25px;
  }
</style>
