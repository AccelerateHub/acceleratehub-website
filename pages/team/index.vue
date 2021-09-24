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
      <div class="row justify-content-between cover mt-5">
        <div v-for="team in teams" :key="team.name" class="team-card m-2">
          <div
            class="team-thumbnail"
            :style="{
              backgroundImage: 'url(' + `/img/team/${team.image}` + ')',
            }"
          />
          <!-- <img class="img" :src="`/img/team/${team.image}`" alt="" /> -->
          <div class="content p-3">
            <div class="name">{{ team.name }}</div>
            <div>{{ team.title }}</div>
            <div class="my-2">
              <a
                v-if="team.linkedin"
                :href="team.linkedin"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  class="social"
                  src="../../assets/entypo-social_linkedin-with-circle.png"
                  alt=""
                />
              </a>
              <a
                v-if="team.twitter"
                :href="team.twitter"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  class="social"
                  src="../../assets/entypo-social_twitter-with-circle.png"
                  alt=""
                />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <FooterNav />
  </div>
</template>

<script>
import teams from '~/static/data/team.js'
export default {
  name: 'Teams',
  data() {
    return {
      teams,
    }
  },
}
</script>

<style scoped>
.team-thumbnail {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 100px;
  height: 40vh;
}
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
  border: 1px solid white;
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
  width: 300px;
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
    margin-left: 3% !important;
    margin-right: 3% !important;
  }
  input {
    width: 100%;
  }
  .team-card {
    width: 100%;
  }
}
</style>
