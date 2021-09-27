<template>
  <div>
    <footer class="p-lg-5 p-3">
      <div class="row px-lg-2 pb-4">
        <div class="col-lg-2 mx-lg-5">
          <div class="heading mb-3">NAVIGATE</div>
          <nuxt-link to="/">
            <div class="py-1">HOME</div>
          </nuxt-link>
          <nuxt-link to="/about">
            <div class="py-1">ABOUT US</div>
          </nuxt-link>
          <nuxt-link to="">
            <div class="py-1">BLOG</div>
          </nuxt-link>
          <nuxt-link to="/team">
            <div class="py-1">OUR TEAM</div>
          </nuxt-link>
        </div>
        <div class="col-lg-1 mx-lg-5">
          <div class="heading mb-3">SOCIALS</div>
          <a href="https://web.facebook.com/acceleratehubng">
            <div class="py-1">FACEBOOK</div>
          </a>
          <a href="https://twitter.com/acceleratehubng">
            <div class="py-1">TWITTER</div>
          </a>
          <a href="https://www.linkedin.com/company/acceleratehubng/">
            <div class="py-1">LINKEDIN</div>
          </a>
          <a href="https://instagram.com/acceleratehubng">
            <div class="py-1">INSTAGRAM</div>
          </a>
          <a href="https://youtube.com/acceleratehubng">
            <div class="py-1">YOUTUBE</div>
          </a>
        </div>
        <div class="col-lg-2 mx-lg-5">
          <div class="heading mb-3">LINKS</div>
          <div class="py-1">
            <input class="p-2 px-4" type="button" value="JOIN US" />
          </div>
          <div class="py-1">
            <nuxt-link to="/contact">
              <input class="p-2 px-4" type="button" value="CONTACT US" />
            </nuxt-link>
          </div>
        </div>
        <div class="col-lg-4 text-lg-right text-left">
          <div class="py-3">
            <img src="../assets/hub-logo.png" alt="" />
          </div>
          <div>
            Accelerate INNOVATION Hub, Advancement and Linkages Centre. Rivers
            State University
          </div>
          <div class="py-3">acceleratehubng@gmail.com</div>
          <div class="py-3">+234 813 - 5126 - 541</div>
        </div>
      </div>
    </footer>
  </div>
</template>
<style scoped>
.row {
  margin-left: 0px !important;
  margin-right: 0px !important;
}
footer {
  background-color: #141212;
  color: white;
  font-size: 13px !important;
  font-weight: 700 !important;
  text-transform: uppercase;
  font-family: 'Montserrat', sans-serif;
}
.heading {
  color: #edf518;
}
input {
  border: 1px solid white;
  background: transparent;
  color: white;
}
img {
  width: 40px;
}
a {
  color: white;
}
a:hover {
  text-decoration: none;
}
</style>
