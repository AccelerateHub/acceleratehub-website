<template>
  <div class="main">
    <HeaderNav />
    <div>
      <div class="row cover py-lg-5">
        <div class="col-lg-3">
          <div class="big p-3 px-lg-5 text-heading">TESTIMONIALS</div>
        </div>
      </div>
      <div class="row cover py-5">
        <div v-for="testimonial in testimonials" :key="testimonial.name" class="col-lg-4 my-3">
          <div class="p-3 testimonial-card p-3">
            <div class="d-flex">
              <img class="user" src="../../assets/Ellipse 2.png" alt="" />
              <div class="pl-3">
                <div class="heading">{{testimonial.name}}</div>
                <div class="stack">UIUX Track</div>
              </div>
            </div>
            <div class="py-3">
              {{testimonial.msg}}
            </div>
          </div>
        </div>
      </div>
    </div>
    <FooterNav />
  </div>
</template>
<script>
import testimonials from '~/static/data/testimonial.js'
export default {
  name: 'Testimonials',
  data() {
    return {
      testimonials,
    }
  },
}
</script>
<style scoped>
.main {
  background-color: #070707 !important;
  color: white;
}
.big {
  text-transform: uppercase;
  font-weight: 600;
  border: 3px solid white;
}
.cover {
  margin-left: 12% !important;
  margin-right: 12% !important;
}
.testimonial-card {
  border: 3px solid #4bb7f4;
  height: 400px;
}
.heading {
  color: #edf518;
  font-weight: 700;
  text-transform: uppercase;
  font-size: 15px;
}
.user {
  width: 40px;
  height: 40px;
}
.stack {
  font-size: 13px;
}
@media (max-width: 600px) {
  .cover {
    margin-left: 3% !important;
    margin-right: 3% !important;
  }
  .testimonial-card {
  height: auto;
}
}
</style>
