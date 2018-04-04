<template>
  <div class="card single-post">
    <div class="card-header">
      Post Title (ID - {{$route.params.id}})
    </div>
    <div class="card-body">
      <h5 class="card-title">Author | Created Date</h5>
      <small>Last Updated</small>
      <p class="card-text">Post content....</p>
      <nuxt-link to="/posts" class="btn btn-primary">Back</nuxt-link>
    </div>
  </div>
</template>
