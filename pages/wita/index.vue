<template>
  <div>
    <HeaderNav />
    <main class="px-lg-0 px-2">
      <section class="page-title pt-5">
        <div class="container">
          <h2 class="px-4 p-2">WOMEN IN TECH IN ACCLERATE</h2>
        </div>
      </section>
      <section class="our-story">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-5">
              <h2>OUR STORY</h2>
              <div class="intro">
                <h4>OUR STORY</h4>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Turpis dictum ac nisl in lectus facilisi. Egestas vestibulum,
                  nullam a commodo adipiscing maecenas pretium tristique quis.
                  Viverra ut ut diam, in. Accumsan felis vestibulum sit id ac.
                  Quisque magna fermentum, congue maecenas in. Nam morbi nibh
                  magnis amet vulputate elementum fames tortor in. Nam sapien
                  sit porta ut suspendisse ipsum neque egestas integer.
                  Habitasse imperdiet metus morbi risus. Faucibus quis nunc
                  arcu, at. Placerat etiam felis urna cras dapibus mauris.
                  Tempus, et diam vulputate viverra vel. Nibh lacus vulputate
                  vitae quam libero diam. Pellentesque tincidunt at pellentesque
                  tellus. Duis interdum vitae velit eget. Consequat, id donec
                  nam aliquam lacus phasellus. Facilisis cras ut egestas
                  bibendum sagittis commodo. Imperdiet adipiscing in praesent
                  dolor pretium. Dolor laoreet natoque neque, fermentum molestie
                  convallis id nec quam. Ut mus vitae lorem sagittis ipsum. Et
                  commodo et, viverra venenatis. In magna tempor mauris.
                </p>
                <h5>LOUIS WHYTE JONAH</h5>
                <p>Product Designer, Accelerate Innovation Hub</p>
              </div>
            </div>
            <div class="col-12 col-md-5">
              <div class="our-story-images">
                <img src="~static/img/bg-face.png" alt="" />
                <img src="~static/img/bg-face-min.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="wita-lead">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-6">
              <img src="~static/img/bg-face-min.png" alt="" />
            </div>
            <div class="col-12 col-md-6">
              <h2>WITA LEAD</h2>
              <div class="wita-text">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. In
                  sit pellentesque cursus faucibus commodo purus in vel. Augue
                  cras at tempus, eu. Amet, nec maecenas leo ornare lectus
                  habitasse ipsum adipiscing urna. Lorem mauris amet in
                  pellentesque.
                </p>
                <h5>NAME OF LEAD</h5>
                <p>Stack of Women in Tech Lead</p>
              </div>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-12 col-md-6">
              <div class="core-item orange">
                <div class="content">
                  <h4>Mission</h4>
                  <p>
                    Student development is the core and the heartbeat of
                    Accelerate innovation hub, this is we plan regular programs
                    and event that enlightens and exposes students to
                    extracurricular technological-based activities and sessions.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item blue">
                <div class="content">
                  <h4>Vision</h4>
                  <p>
                    We also center our energy on the developing tech solutions
                    that would solve problems in our community and nation at
                    large and imprve the cost of living. Focusing majorly on UN
                    SDGs.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="core-values">
        <div class="container">
          <h2 class="p-3">CORE VALUES</h2>
          <div class="row">
            <div class="col-12 col-md-6">
              <div class="core-item orange">
                <div class="content">
                  <h4>Student Development</h4>
                  <p>
                    Student development is the core and the heartbeat of
                    Accelerate innovation hub, this is we plan regular programs
                    and event that enlightens and exposes students to
                    extracurricular technological-based activities and sessions.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item blue">
                <div class="content">
                  <h4>TECH Solutions</h4>
                  <p>
                    We also center our energy on the developing tech solutions
                    that would solve problems in our community and nation at
                    large and imprve the cost of living. Focusing majorly on UN
                    SDGs.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item white">
                <div class="content">
                  <h4>
                    Virtual Reality / Augmented Reality (VR/AR) Development
                  </h4>
                  <p>
                    Pushing the barriers of technology with VR/AR, starting with
                    its development, we aim to bring digital solutions to
                    Varsities, solving technical problems and tech innovations
                    through learning.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item yellow">
                <div class="content">
                  <h4>Agriculture Technology</h4>
                  <p>
                    As our economy continues to expand the need for an expansion
                    in the agricultural sector is on the increase this is why as
                    a technologically based community we seek ways that
                    technology can be integrated into agriculture to foster the
                    growth and expansion of the agricultural sector.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <FooterNav />
  </div>
</template>

<script>
export default {
  name: 'WITA',
}
</script>

<style scoped>
h2 {
  font-size: 20px;
  font-weight: 600;
  padding-top: 10px;
  padding-bottom: 10px;
}
h4 {
  text-transform: uppercase;
  font-weight: 600;
  font-size: 18px;
}
.page-title {
  margin-top: 20px;
  margin-bottom: 80px;
}
.page-title h2 {
  padding: 5px;
  border: 3px solid var(--bg-color);
  width: 289px;
}
.our-story {
  margin-top: 30px;
  margin-bottom: 30px;
}

.our-story h2 {
  padding: 5px;
  border: 3px solid var(--bg-color);
  text-align: center;
  margin-bottom: 20px;
}

.intro {
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 3px solid var(--light-blue);
  margin-bottom: 20px;
}

.intro h5 {
  color: var(--bg-yellow);
}

.our-story-images img {
  width: 100%;
}

.our-story-images img:last-child {
  margin-top: 40px;
}

/* WITA LEAD */

.wita-lead {
  margin-top: 40px;
  margin-bottom: 40px;
}

.wita-lead img {
  width: 100%;
  margin-bottom: 20px;
}

.wita-lead h2 {
  border: 3px solid #fff;
  text-align: center;
}

.wita-text {
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 3px solid var(--light-blue);
  background-color: var(--bg-dark-blue);
}

.wita-text h5 {
  color: var(--bg-yellow);
}
.core-values {
  margin-bottom: 80px;
}
.core-values h2 {
  width: 300px;
  text-align: center;
  padding: 5px;
  border: 3px solid var(--bg-color);
}
.core-item {
  padding: 30px;
  border: 2px solid #fff;
  margin-top: 20px;
}

.yellow {
  border: 3px solid #edf518;
}
.orange {
  border: 3px solid #fa6b43;
}
.blue {
  border: 3px solid #4bb7f4;
}
.white {
  border: 3px solid #fff;
}
@media (max-width: 800px) {
  p {
    font-size: 13px;
  }
}
@media (min-width: 1000px) {
  .page-title h2 {
    width: 350px;
  }
  .our-story h2 {
    padding: 10px;
  }
  .intro {
    position: relative;
    padding: 40px;
    border: 3px solid var(--light-blue);
    z-index: 1000;
    width: 597px;
  }
  .our-story-images img {
    width: 635px;
  }

  .wita-lead img {
    width: 100%;
    height: 293px;
    margin-bottom: 0px;
  }

  /* CORE VALUES */
  .core-item {
    display: flex;
    align-items: center;
    height: 300px;
  }
}
</style>
