<template>
  <div class="my-4">
    <carousel :autoplay="true" :nav="false" :loop="true" :responsive="{0:{items:1,nav:false},900:{items:2,nav:false},1200:{items:3}}">
      <div class="m-3"><img src="../assets/Rectangle 30.png" /></div>
    </carousel>
  </div>
</template>
<script>
import carousel from 'vue-owl-carousel'
export default {
  components: { carousel },
}
</script>
