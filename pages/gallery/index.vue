<template>
  <div>
    <HeaderNav />
    <div class="container">
      <div class="row justify-content-around my-4">
        <div v-for="user in gallery" :key="user.image" class="m-3 col-lg-3">
          <img class="team-img" :src="'img/Gallery/' + user.image" />
        </div>
      </div>
    </div>
    <FooterNav />
  </div>
</template>
<script>
import gallery from '~/static/data/gallery.js'
export default {
  name: 'Gallery',
  data() {
    return {
      gallery,
    }
  },
}
</script>
<style scoped>
img {
  width: 100%;
}
</style>
