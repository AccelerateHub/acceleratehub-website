<template>
  <nav>
    <div id="mobile-nav" class="d-flex justify-content-between p-3 px-4">
      <NuxtLink to="/">
        <img class="logo" src="../assets/hub-logo.png" alt="" />
      </NuxtLink>
      <img @click="openNav" src="../assets/menu.svg" alt="" />
    </div>
    <div class="nav p-3">
      <NuxtLink to="/">
        <div class="pt-2">HOME</div>
      </NuxtLink>
      <NuxtLink to="/about">
        <div class="pt-2">ABOUT US</div>
      </NuxtLink>
      <NuxtLink to="/projects">
        <div class="pt-2">PROJECTS</div>
      </NuxtLink>
      <NuxtLink to="/team">
        <div class="pt-2">OUR TEAM</div>
      </NuxtLink>
      <div>
        <NuxtLink to="/">
          <img src="../assets/hub-logo.png" alt="" />
        </NuxtLink>
      </div>
      <NuxtLink to="/wita">
        <div class="pt-2">WITA</div>
      </NuxtLink>
      <NuxtLink to="/testimonials">
        <div class="pt-2">TESTIMONIALS</div>
      </NuxtLink>
      <a href="https://www.medium.com/@acceleratehubng">
        <div class="pt-2">BLOG</div>
      </a>
      <NuxtLink to="/contact">
        <div class="pt-2">CONTACT US</div>
      </NuxtLink>
    </div>

    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav"
        >&times;</a
      >
      <div class="ml-4">
        <img src="../assets/hub-logo.png" alt="" />
      </div>
      <NuxtLink to="/">
        <div class="py-3">HOME</div>
      </NuxtLink>
      <NuxtLink to="/about">
        <div class="py-3">ABOUT US</div>
      </NuxtLink>
      <NuxtLink to="/projects">
        <div class="py-3">PROJECTS</div>
      </NuxtLink>
      <NuxtLink to="/team">
        <div class="py-3">OUR TEAM</div>
      </NuxtLink>
      <NuxtLink to="/wita">
        <div class="py-3">WITA</div>
      </NuxtLink>
      <NuxtLink to="/testimonials">
        <div class="py-3">TESTIMONIALS</div>
      </NuxtLink>
      <a href="https://www.medium.com/@acceleratehubng">
        <div class="py-3">BLOG</div>
      </a>
      <NuxtLink to="/contact">
        <div class="py-3">CONTACT US</div>
      </NuxtLink>
    </div>
  </nav>
</template>
<script>
export default {
  data() {
    return {}
  },
  methods: {
    /* Open the sidenav */
    openNav() {
      document.getElementById('mySidenav').style.width = '100%'
    },
    /* Close/hide the sidenav */
    closeNav() {
      document.getElementById('mySidenav').style.width = '0'
    },
  },
}
</script>
<style scoped>
.nav {
  font-family: 'Montserrat', sans-serif;
  width: 75%;
  display: flex;
  justify-content: space-between;
  margin-left: auto;
  margin-right: auto;
  color: white;
}
a {
  color: white !important;
  font-weight: 700 !important;
}
div {
  font-weight: 700 !important;
  font-size: 14px !important;
}
.nav img,
.logo {
  width: 40px;
}
#mobile-nav {
  display: none !important;
}
/* The side navigation menu */
.sidenav {
  height: 100%; /* 100% Full-height */
  width: 0; /* 0 width - change this with JavaScript */
  position: fixed; /* Stay in place */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  text-align: left;
  background-color: #070707; /* Black*/
  overflow-x: hidden; /* Disable horizontal scroll */
  padding-top: 60px; /* Place content 60px from the top */
  transition: 0.5s; /* 0.5 second transition effect to slide in the sidenav */
}

/* The navigation menu links */
.sidenav div,
a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #fff;
  display: block;
  transition: 0.3s;
}

/* When you mouse over the navigation links, change their color */
.sidenav div:hover {
  color: #4bb7f4;
}

/* Position and style the close button (top right corner) */
.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

/* Style page content - use this if you want to push the page content to the right when you open the side navigation */
#main {
  transition: margin-left 0.5s;
  padding: 20px;
}

/* On smaller screens, where height is less than 450px, change the style of the sidenav (less padding and a smaller font size) */
@media screen and (max-height: 450px) {
  .sidenav {
    padding-top: 15px;
  }
  .sidenav a {
    font-size: 18px;
  }
}
@media (max-width: 900px) {
  .nav {
    width: 90%;
  }
}
@media (max-width: 800px) {
  .nav {
    display: none;
  }
  #mobile-nav {
    display: flex !important;
  }
}
</style>
