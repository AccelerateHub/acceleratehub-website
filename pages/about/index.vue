<template>
  <div>
    <main>
      <HeaderNav />
      <section class="our-story">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-5">
              <h2>OUR STORY</h2>
              <div class="intro">
                <h4>ACCELERATE INNOVATION HUB</h4>
                <p>In February 2004, in a dorm room at Harvard University Mark Zuckerberg, launched a website that is currently worth over $600+ Billion, now that is the part of the narrative that is popular. It is my belief that Mark had his environment as an added advantage to further foster the growth and rapid expansion of Facebook, and I must say that in Rivers State University there are Mark Zuckerberg’s and Bill Gate’s who are yet to be seen simply because the needed environment that will encourage their growth has not been created. The dream of the Accelerate hub is to create that enabling environment and encourage innovation even in our school ecosystem, not just leaving students to follow the conventional methodology of “graduate first, think later”. With the establishment of the accelerate innovation hub, student tech startups would finally get a platform to easily work, innovate, collaborate and synergize with other tech startups and other experts outside their reach to motivate, inspired, and tutor them.</p>
                <h5>GODWIN JIMMY</h5>
                <p>Founder, Accelerate Innovation Hub</p>
              </div>
            </div>
            <div class="col-12 col-md-5">
              <div class="our-story-images">
                <img src="~static/img/bg-face.png" alt="">
                <img src="~static/img/bg-face-min.png" alt="">
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="about-us">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-6">
              <div class="heading-mobile">
                <h2>ABOUT US</h2>
              </div>
              <img src="~static/img/bg-face-min.png" alt="">
            </div>
            <div class="col-12 col-md-6">
              <div class="heading">
                <h2>ABOUT US</h2>
              </div>
              <div class="about-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In sit pellentesque cursus faucibus commodo purus in vel. Augue cras at tempus, eu. Amet, nec maecenas leo ornare lectus habitasse ipsum adipiscing urna. Lorem mauris amet in pellentesque.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="partners">
        <div class="container">
          <h2>OUR PARTNERS</h2>
        </div>
      </section>

      <section class="core-values">
        <div class="container">
          <h2>CORE VALUES</h2>
          <div class="row">
            <div class="col-12 col-md-6">
              <div class="core-item orange">
                <div class="content">
                  <h4>Student Development</h4>
                  <p>Student development is the core and the heartbeat of Accelerate innovation hub, this is we plan regular programs and event that enlightens and exposes students to extracurricular technological-based activities and sessions.</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item blue">
                <div class="content">
                  <h4>TECH Solutions</h4>
                  <p>We also center our energy on the developing tech solutions that would solve problems in our community and nation at large and imprve the cost of living. Focusing majorly on UN SDGs.</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item white">
                <div class="content">
                  <h4>Virtual Reality / Augmented Reality (VR/AR) Development</h4>
                  <p>Pushing the barriers of technology with VR/AR, starting with its development, we aim to bring digital solutions to Varsities, solving technical problems and tech innovations through learning.</p>
                </div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="core-item yellow">
                <div class="content">
                  <h4>Agriculture Technology</h4>
                  <p>As our economy continues to expand the need for an expansion in the agricultural sector is on the increase this is why as a technologically based community we seek ways that technology can be integrated into agriculture to foster the growth and expansion of the agricultural sector.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <FooterNav />
    </main>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style scoped>
.our-story {
  margin-top: 30px;
  margin-bottom: 30px;
}
.our-story h2 {
  padding: 5px;
  border: 6px solid var(--bg-color);
  text-align: center;
  margin-bottom: 20px;
}

.intro {
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 6px solid var(--light-blue);
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

/* About styles */

.about-us {
  margin-top: 45px;
  margin-bottom: 30px;
}
.heading {
  display: none;
}
.about-us img {
  width: 100%;
}

.about-us h2 {
  text-align: center;
  padding: 5px;
  border: 6px solid var(--bg-color);
  margin-bottom: 20px;
}

.about-content {
  margin-top: 10px;
  background-color: var(--bg-dark-blue);
  padding: 20px;
  border: 6px solid var(--light-blue);
  margin-bottom: 20px;
}

/* Partners */
.partners{
  margin-top: 30px;
  margin-bottom: 30px;
}
.partners h2 {
  padding: 5px;
  border: 5px solid var(--bg-color);
  width: 300px;
  text-align: center;
}

/* CORE VALUES */
.core-values {
  margin-bottom: 80px;
}
.core-values h2 {
  width: 300px;
  text-align: center;
  padding: 5px;
  border: 6px solid var(--bg-color);
}
.core-item {
  padding: 30px;
  border: 2px solid #fff;
  margin-top: 20px;
}

.yellow {
    border: 3px solid #EDF518;
  }
  .orange {
    border: 3px solid #FA6B43;
  }
  .blue {
    border: 3px solid #4BB7F4;
  }
  .white {
    border: 3px solid #fff;
  }

@media (min-width: 1000px) {
  .our-story h2 {
    padding: 10px;
  }
  .intro {
    position: relative;
    padding: 40px;
    border: 6px solid var(--light-blue);
    z-index: 1000;
    width: 597px;
  }
  .our-story-images img {
    width: 635px;
  }

  /* About styles */
  .about-us img {
    width: 635px;
  }
  .heading {
    display: flex;
    justify-content: flex-end;
  }
  .heading-mobile {
    display: none;
  }
  .about-us h2 {
    width: 300px;
  }
  .about-content {
    margin-top: 0px;
    border: 6px solid var(--light-blue);
    padding: 30px;
  }

  /* CORE VALUES */
  .core-item {
    display: flex;
    align-items: center;
    height: 300px;
  }
}


</style>
