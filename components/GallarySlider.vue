<template>
  <div class="my-4">
    <carousel
      :autoplay="true"
      :nav="false"
      :loop="true"
      :dots="false"
      :responsive="{
        0: { items: 1, nav: false },
        900: { items: 2, nav: false },
        1200: { items: 3 },
      }"
    >
      <div v-for="user in gallery" :key="user.image" class="m-lg-3">
        <img class="team-img" :src="'img/Gallery/' + user.image" />
      </div>
    </carousel>
  </div>
</template>
<script>
import gallery from '~/static/data/gallery.js'
import carousel from 'vue-owl-carousel'
export default {
  components: { carousel },

  name: 'Gallery',
  data() {
    return {
      gallery,
    }
  },
}
</script>
<style scoped>

</style>
