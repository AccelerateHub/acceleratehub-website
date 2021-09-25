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
        1200: { items: 3 },
      }"
    >
      <div
        v-for="testimonial in testimonials"
        :key="testimonial.name"
        class="m-lg-3"
      >
        <div class="p-3 testimonial-card p-3">
          <div class="d-flex">
            <img class="user" src="../assets/Ellipse 2.png" alt="" />
            <div class="pl-3">
              <div class="heading">{{ testimonial.name }}</div>
              <div class="stack">{{testimonial.stack}}</div>
            </div>
          </div>
          <div class="py-3 text">
            {{ testimonial.msg }}
          </div>
        </div>
      </div>
    </carousel>
  </div>
</template>
<script>
import carousel from 'vue-owl-carousel'
import testimonials from '~/static/data/testimonial.js'

export default {
  name: 'Testimonials',
  components: { carousel },
  data() {
    return {
      testimonials,
    }
  },
}
</script>
<style scoped>
.testimonial-card {
  border: 1px solid #4bb7f4;
  height: 330px;
}
.heading {
  color: #edf518;
  font-weight: 700;
  text-transform: uppercase;
  font-size: 15px;
}
.user {
  width: 40px !important;
  height: 40px;
}
.stack {
  font-size: 13px;
}
.text {
  font-size: 14px;
}
@media (max-width: 600px) {
  .text {
    font-size: 13px;
  }
  .testimonial-card {
    height: auto;
  }
}
</style>
