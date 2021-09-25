<template>
  <div class="my-4">
    <carousel
      :autoplay="true"
      :nav="false"
      :loop="true"
      :dots="true"
      :responsive="{
        0: { items: 1, nav: false },
        900: { items: 2, nav: false },
        1200: { items: 4 },
      }"
    >
      <div class="m-2">
        <img src="~/static/img/IMG-20210830-WA0116 - Grace Orji 1.png" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/IMG-20210720-WA0018_1626796948541 - alabere daisy 1.png" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/IMG-20201008-WA0008 - Ruth Charles 1.png" alt="" />
      </div>
    </carousel>
  </div>
</template>
<script>
import carousel from 'vue-owl-carousel'
export default {
  components: { carousel },
}
</script>
<style scoped></style>
