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
        <img src="~/static/img/wita/IMG-20210830-WA0116 - Grace Orji 1.png" alt="" />
      </div>
      <div class="m-2">
        <img
          src="~/static/img/wita/IMG-20210720-WA0018_1626796948541 - alabere daisy 1.png"
          alt=""
        />
      </div>
      <div class="m-2">
        <img
          src="~/static/img/wita/IMG-20201008-WA0008 - Ruth Charles 1.png"
          alt=""
        />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/bekky.jpeg" alt="" />
      </div>

      <div class="m-2">
        <img src="~/static/img/wita/BlessingA.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Boma.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/David Theodora.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/EDMUND.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Eunice Ebelike.JPG" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Favour.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/GIFT KENNETH GIGI.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Gold.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Grace.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/ifeoma.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Jacia Ebubechi.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Jane.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Jennifer.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Jubilee Afia.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Ojekudo victory Onaefe.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Precious Awa.jpg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/salami.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Stella nteiren.JPG" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Tinuke.jpeg" alt="" />
      </div>
      <div class="m-2">
        <img src="~/static/img/wita/Ufuoma Dick Moses.jpeg" alt="" />
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
<style scoped>
img{
  height: 280px;
}
</style>
