<template>
  <div class="main">
    <HeaderNav />
    <div>
      <div class="row cover mt-5 justify-content-between">
        <div class="col-lg-3">
          <div class="big p-3 px-lg-5 text-heading">our team</div>
        </div>
        <div class="col-lg-3 pt-3 text-whire">
          <input class="p-1 px-3" type="text" placeholder="SEARCH TEAM" />
        </div>
      </div>
      <div class="row cover mt-5">
        <div
          v-for="team in teams"
          :key="team.name"
          class="team-card m-2"
        >
          <img class="img" :src="`/img/team/${team.image}`" alt="" />
          <div class="content p-3">
            <div class="name">{{ team.name }}</div>
            <div>{{ team.title }}</div>
            <div class="my-2">
              <img
                class="social"
                src="../../assets/entypo-social_linkedin-with-circle.png"
                alt=""
              />
              <img
                class="social"
                src="../../assets/entypo-social_twitter-with-circle.png"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <FooterNav />
  </div>
</template>

<script>
import teams from '~/static/data/team.js';
export default {
  name: 'Teams',
  data () {
    return {
      teams
    }
  }
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
}
.cover {
  margin-left: 12% !important;
  margin-right: 12% !important;
}
.text-heading {
  border: 3px solid white;
}
input {
  background: transparent;
  border: 1px solid white;
  color: white;
}
input::placeholder {
  color: white;
}
.team-card {
  background-color: #060611;
}
.name {
  color: #edf518;
  font-weight: 700;
  text-transform: uppercase;
}
.img {
  width: 100%;
}
.content {
  font-weight: 500;
}
.social {
  width: 20px;
}
@media (max-width: 800px) {
  .cover {
    margin-left: 0% !important;
    margin-right: 0% !important;
  }
  input{
    width: 100%;
  }
}
</style>
