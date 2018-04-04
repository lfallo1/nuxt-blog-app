<template>

    <div class="container home-page">
      <div class="row">
        <SiteIntro />
      </div>
      <div class="row">
        <PostPreview id="1" title="1st post" previewText="Preview text for the post" />
        <PostPreview id="2" title="2nd post" previewText="Preview text for the 2nd post" />
        <PostPreview id="3" title="3rd post" previewText="Preview text for the 3rd post" />
      </div>
    </div>

</template>

<script>

import Logo from '~/components/Logo.vue'
import UserTable from '~/components/UserTable.vue'
import PostPreview from '~/components/PostPreview.vue'
import SiteIntro from '~/components/SiteIntro.vue'

export default {
  components: {
    Logo,
    UserTable,
    PostPreview,
    SiteIntro
  }
}
</script>

<style>

</style>
