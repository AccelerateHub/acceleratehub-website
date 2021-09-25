<template>
  <div class="my-4">
    <carousel
      :autoplay="true"
      :nav="false"
      :loop="true"
      :dots="true"
      :responsive="{
        0: { items: 1, nav: false },
        900: { items: 3, nav: false },
        1200: { items: 4 },
      }"
    >
      <div v-for="partner in partners" :key="partner.name" class="m-lg-3">
        <img class="team-img" :src="'img/partners/' + partner.image" />
      </div>
    </carousel>
  </div>
</template>
<script>
import partners from '~/static/data/partners.js'
import carousel from 'vue-owl-carousel'
export default {
  components: { carousel },

  name: 'Partners',
  data() {
    return {
      partners,
    }
  },
}
</script>
<style scoped>

</style>
