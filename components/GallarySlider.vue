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
      <div v-for="team in teams" :key="team.name" class="m-lg-3">
        <img class="team-img" :src="'img/team/' + team.image" />
      </div>
    </carousel>
  </div>
</template>
<script>
import teams from '~/static/data/team.js'
import carousel from 'vue-owl-carousel'
export default {
  components: { carousel },

  name: 'Teams',
  data() {
    return {
      teams,
    }
  },
}
</script>
<style scoped>
.team-img {
  height: 300px;
}
</style>
