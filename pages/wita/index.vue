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
                  The world is filled with male in dominance of the tech space, thus, we can say that women are poorly represented in technology as well as other parts of STEM.
                </p>
                <p>
                  Research may tell you that women in tech globally are about 30% to 40% at an average, not only are they poorly represented but they are also underpaid.
                </p>
                <p>
                  Why this tendering gap, why the bridge in technology?
                  Few reasons for this are; The ideology that people have in this part of the world that tech is meant for guys and that females  shouldnt advance in their career.
                </p>
                <p>
                  Women in Tech in Accelerate is a section of Accelerate Innovation Hub that tends to bridge this gap by promoting digital inclusion for all, gender equality and equal opportunities for everyone. We hope to achieve this by having an enabling environment to advance more women into tech.
                </p>
                <h5>LOUIS WHYTE JONAH</h5>
                <p>Product Designer, Accelerate Innovation Hub</p>
              </div>
            </div>
            <div class="col-12 col-md-5">
              <div class="our-story-images">
                <img src="~static/img/Rectangle 26.png" alt="" />
                <div class="d-flex p-lg-2 ml-lg-5 pl-lg-5">
                  <img
                    class="mx-lg-4 wita-img"
                    src="~static/img/45 1.png"
                    alt=""
                  />
                  <img
                    class="wita-img"
                    src="~static/img/46 1.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="wita-lead">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-6">
              <img  src="~static/img/team/Favour.png" alt="" />
            </div>
            <div class="col-12 col-md-6">
              <h2>WITA LEAD</h2>
              <div class="wita-text">
                <p>
                  It is neither his world nor her world rather it is our world, our technology. Thus, we opine the embrace of inclusion and equal opportunities to better our world through STEM.
                </p>
                <h5>FAVOUR AYOZIE</h5>
                <p>Lead, Women in Tech Accelerate</p>
              </div>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-12 col-md-6">
              <div class="core-item orange">
                <div class="content">
                  <h4>Mission</h4>
                  <p>
                    Our mission is to make sure women are well represented in the industry by providing an avenue for them to use technology for social good
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item blue">
                <div class="content">
                  <h4>Vision</h4>
                  <p>
                    To bridge the digital divide in women in tech by creating more opportunties and proper guidance in the tech space.
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
                  <h4>INTERDiversity</h4>
                  <p>
                    We aim to produce a more efficient and better ability to make crucial decisions through Women. By presenting them with their skills, creativity and talents which are a plus for the tech solutions & world.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item blue">
                <div class="content">
                  <h4>INNOVATIVE MINDS</h4>
                  <p>
                    By building Women in tech, we allow their innovative minds to play an important role to understanding the specific needs of women in certain areas. This can represent women and the consumer needs.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item white">
                <div class="content">
                  <h4>
                    GENDER EQUALITY
                  </h4>
                  <p>
                    We create an environment that pushes and supports women into tech. With networking opportunities that allows them to explore and develop, we aim to close Gender Gap and Inequality balance.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item yellow">
                <div class="content">
                  <h4>COLLABORATION</h4>
                  <p>
                    By creating an environment for them to collaborate with other groups and women who are already creating solutions in the tech space. Also to enable them share ideas freely and create solutions.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section>
        <div class="row mx-lg-5 px-lg-5">
          <div class="col-lg-4 m-lg-2">
            <div class="big text-heading p-3">meet face of wita</div>
          </div>
          <div class="col-12">
            <FaceOfWitaSlider />
          </div>
          <div class="col-12 my-5">
            <Socials />
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
  border: 1px solid var(--bg-color);
  width: 289px;
}
.our-story {
  margin-top: 30px;
  margin-bottom: 30px;
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
.our-story h2 {
  padding: 5px;
  border: 1px solid var(--bg-color);
  text-align: center;
  margin-bottom: 20px;
}

.intro {
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 1px solid var(--light-blue);
  margin-bottom: 20px;
}

.intro h5 {
  color: var(--bg-yellow);
}

.our-story-images img {
  width: 100%;
}

/* .our-story-images img:last-child {
  margin-top: 40px;
} */

/* WITA LEAD */

.wita-lead {
  margin-top: 40px;
  margin-bottom: 40px;
}

.wita-lead img {
  width: 50%!important;
  margin-bottom: 20px;
  height: 50vh!important;
  margin-left: 200px!important;
}
.wita-lead h2 {
  border: 1px solid #fff;
  text-align: center;
}

.wita-text {
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 1px solid var(--light-blue);
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
  border: 1px solid var(--bg-color);
}
.core-item {
  padding: 30px;
  border: 1px solid #fff;
  margin-top: 20px;
}

.yellow {
  border: 1px solid #edf518;
}
.orange {
  border: 1px solid #fa6b43;
}
.blue {
  border: 1px solid #4bb7f4;
}
.white {
  border: 1px solid #fff;
}
.wita-img :first-child {
  width: 100%;
  height: 150px;
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
    border: 1px solid var(--light-blue);
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
  .wita-lead img {
  margin-left: 0px;
}
}
</style>
