<template>
  <div>
    <div class="row py-lg-5">
      <div
        class="
          col-lg-4 col-md-5 col-sm-5 col-xs-5
          mx-auto
          text-white text-center
          py-5
          my-5
        "
      >
        <div class="py-5">
          <div class="heading">
            learn, create, innovate, <span>collaborate</span>
          </div>
          <div class="title">accelerate innovation hub</div>
        </div>
      </div>
    </div>
    <div>
      <img class="frame-3" src="../assets/frame.png" alt="" />
      <img class="frame-1" src="../assets/avatar-frame.png" alt="" />
      <img class="frame-2" src="../assets/frame-1.png" alt="" />
    </div>
    <div>
      <img class="frame-4" src="../assets/frame-4.png" alt="" />
      <img class="frame-5" src="../assets/frame-2.png" alt="" />
      <img class="frame-6" src="../assets/frame-3.png" alt="" />
    </div>
    <div class="row justify-content-between cover pt-5">
      <div class="col-lg-6">
        <div class="big p-3 px-lg-5 text-heading">student development</div>
        <div class="about px-lg-5 p-3 py-4 my-4">
          <div class="big pb-2 name">ACCELERATE INNOVATION HUB</div>
          <div class="text">
            Accelerate Innovation Hub is a tech community that facilitates
            development in technology, entrepreneurship, through mentorship,
            trainings, collaboration, events etc. with the hope of building a
            digital ecosystem for young people while solving problem in our
            community using technology and especially United Nations Sustainable
            Development Goals 4 (Quality Education), 5 (Gender Equality) and 11
            (Sustainable cities and communities).
          </div>
          <div class="mt-3">
            <input class="p-3 px-5 btn1" type="button" value="KNOW MORE" />
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="big p-3 px-lg-5 blue mb-3">our core focus</div>
        <div class="big p-3 px-lg-5 my-3 text-heading">student development</div>
        <div class="big p-3 px-lg-5 my-3 text-heading">TECH Solutions</div>
        <div class="big p-3 px-lg-5 my-3 text-heading">
          Virtual Reality / Augmented Reality (VR/AR) Development
        </div>
        <div class="big p-3 px-lg-5 my-3 text-heading">
          agriculture technology
        </div>
      </div>
    </div>
    <div class="row cover justify-content-center py-5">
      <div
        class="
          col-lg-6
          about
          my-lg-auto
          overlay-1
          col-lg-5
          p-3
          px-lg-5
          py-4
          my-4
          col-lg-m-0
          m-3
        "
      >
        <div class="big pb-2 name">WOMEN IN TECH IN ACCELERATE</div>
        <div class="text">
          Women in Tech In Accelerate was created to foster collaboration and
          synergy amonsgt women in technology. Also to promote gender equity in
          technology through trainings, collaboration, mentorship and supports
          and opportunities for all WITA members.
        </div>
        <div class="mt-3">
          <input class="p-3 px-5 btn2" type="button" value="KNOW MORE" />
        </div>
      </div>
      <div class="col-lg-5">
        <img class="img-1" src="../assets/Rectangle 24.png" alt="" />
      </div>
    </div>
    <div class="row cover justify-content-between my-4">
      <div class="col-lg-4">
        <div class="big p-3 px-lg-5 text-heading">our gallery</div>
      </div>
      <div class="col-lg-3">
        <NuxtLink to="/gallery">
          <div class="big p-3 px-lg-5 text-heading">see more</div>
        </NuxtLink>
      </div>
      <div class="col-12">
        <GallarySlider />
      </div>
    </div>
    <div class="row cover my-4">
      <div class="col-lg-4">
        <div class="big p-3 px-lg-5 text-heading">testimonials</div>
      </div>
      <div class="col-12">
        <TestimonialSlider />
      </div>
    </div>
    <div class="row justify-content-between my-5 cover">
      <div class="col-lg-6">
        <div class="big p-3 px-lg-5 text-heading">accelrate & sdg</div>
        <div class="about px-lg-5 p-3 py-4 my-4">
          <div class="big pb-2 name">UN SUSTAINBLE DEVELOPMENT GOALS</div>
          <div class="pb-lg-5 mb-3 text">
            Accelerate Innovation Hub is focused on solving few SDG goals, as
            part of our commitment to a better society and world.
            <br /><br />
            We are committed to solving SDG 4, 5, and 11, which are “Quality
            Education, Gender Equality and Sustainable cities” respectively.
            <br /><br />
            Having that in our agenda, we have put in place, different programs,
            projects, and guides that will help us accomplish that.
          </div>
          <!-- <div class="mt-3">
            <input class="p-3 px-5 btn1" type="button" value="KNOW MORE" />
          </div> -->
        </div>
      </div>
      <div class="col-lg-3">
        <div class="big p-4 blue mb-2">
          quality education
          <div class="my-3">
            <input class="px-4 p-3 btn3" type="button" value="View Projects" />
          </div>
        </div>
        <div class="big p-4 blue mb-3">
          gender equality
          <div class="my-3">
            <input class="px-4 p-3 btn3" type="button" value="View Projects" />
          </div>
        </div>
        <div class="big p-4 blue">
          sustainable cities & communities
          <div class="my-3">
            <input class="px-4 p-3 btn3" type="button" value="View Projects" />
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <img
          class="sdg-img mb-lg-3"
          src="../assets/E_SDG goals_icons-individual-rgb-04 1.png"
          alt=""
        />
        <img
          class="sdg-img mb-lg-3 mt-lg-1"
          src="../assets/E_SDG goals_icons-individual-rgb-05 1.png"
          alt=""
        />
        <img
          class="sdg-img mt-lg-2"
          src="../assets/E_SDG goals_icons-individual-rgb-11 1.png"
          alt=""
        />
      </div>
    </div>
  </div>
</template>
<style scoped>
@keyframes floating {
  0% {
    transform: translate(0, 0px);
  }
  50% {
    transform: translate(0, 15px);
  }
  100% {
    transform: translate(0, -0px);
  }
}
@keyframes heartBeat {
  from {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
  to {
    transform: scale(1.1);
  }
}

.frame-2,
.frame-5 {
  animation-name: heartBeat;
  animation: heartBeat 0.66s alternate;
  animation-iteration-count: infinite;
}
.frame-1,
.frame-3,
.frame-4,
.frame-6 {
  animation-name: floating;
  animation-duration: 5s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}
.row {
  margin-right: 0px !important;
  margin-left: 0px !important;
}
.heading {
  font-size: 50px;
  text-transform: uppercase;
}
.title {
  font-size: 13px;
  text-transform: uppercase;
}
.heading span {
  color: #edf518;
  font-weight: 900;
}
.frame-1 {
  position: absolute;
  top: 85%;
  left: 13%;
  width: 60px;
}
.frame-2 {
  position: absolute;
  top: 52%;
  left: 26%;
  width: 60px;
}
.frame-3 {
  position: absolute;
  top: 20%;
  left: 13%;
  width: 70px;
}
.frame-4 {
  position: absolute;
  top: 20%;
  right: 13%;
  width: 75px;
}
.frame-5 {
  position: absolute;
  top: 52%;
  right: 26%;
  width: 75px;
}
.frame-6 {
  position: absolute;
  top: 85%;
  right: 13%;
  width: 60px;
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
.blue {
  border: 1px solid #4bb7f4;
}
.about {
  background-color: #060611;
  border: 1px solid #4bb7f4;
}
.btn1 {
  border: none;
  background-color: #4bb7f4;
  font-weight: 600;
  font-size: 12px;
}
.btn2 {
  background-color: #edf518 !important;
  font-weight: 600;
  font-size: 12px;
  border: none;
}
.name {
  width: 200px;
}
.img-1 {
  width: 120%;
  margin-left: -10%;
}
.overlay-1 {
  height: 22% !important;
}
.btn3 {
  background-color: #fff !important;
  font-weight: 600;
  font-size: 12px;
  border: none;
}
.sdg-img {
  height: 23%;
}
a{
  color: white;
  text-decoration: none;
}
@media (max-width: 800px) {
  .heading {
    font-size: 35px;
  }
  .cover {
    margin-left: 3% !important;
    margin-right: 3% !important;
  }
  .frame-1,
  .frame-2,
  .frame-3,
  .frame-4,
  .frame-5,
  .frame-6 {
    width: 40px;
  }
  .frame-6,
  .frame-1 {
    top: 70%;
  }
  .frame-5,
  .frame-2 {
    top: 60%;
  }
  .img-1 {
    width: 100%;
    margin-left: 0%;
  }
  .overlay-1 {
    height: auto !important;
    padding-right: 0% !important;
    margin-right: 0%;
  }
  .text {
    font-size: 13px;
  }
  .big {
    font-size: 15px;
  }
  .sdg-img {
    height: auto !important;
    width: 32%;
  }
}
@media (max-width: 600px) {
  .frame-2, .frame-5{
    top: 65%;
  }
}
</style>
