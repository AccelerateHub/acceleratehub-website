<template>
  <div class="main">
    <HeaderNav />
    <div>
      <div class="row mt-5 cover">
        <div class="col-lg-3">
          <div class="big p-3 px-lg-5 text-heading">contact us</div>
        </div>
      </div>
      <div class="row mt-5 cover">
        <div class="col-12">
          <div class="d-lg-flex">
            <div class="first mr-5">
              <label>FIRST NAME</label><br />
              <input class="p-2" type="text" />
            </div>
            <div class="last">
              <label>last NAME</label><br />
              <input class="p-2" type="text" />
            </div>
          </div>
          <div class="mt-3">
            <label>email address</label><br />
            <input class="p-2" type="text" />
          </div>
          <div class="mt-3">
            <label>reason for mail</label><br />
            <input class="p-2" type="text" />
          </div>
          <div class="mt-3">
            <label>message</label><br />
            <textarea rows="10"></textarea>
          </div>
          <div class="big send text-center my-5 p-3 px-lg-5 text-heading">
            send
          </div>
        </div>
      </div>
    </div>
    <div class="cover my-5">
    <Socials />
    </div>
    <FooterNav />
  </div>
</template>
<style scoped>
.main {
  background-color: #070707 !important;
  color: white;
}
.big {
  text-transform: uppercase;
  font-weight: 600;
}
.send {
  width: 25% !important;
}
.cover {
  margin-left: 12% !important;
  margin-right: 12% !important;
}
.text-heading {
  border: 5px solid white;
}
input,
textarea {
  width: 100%;
  background: transparent;
  border: 1px solid #4bb7f4;
}
label {
  font-size: 13px;
  text-transform: uppercase;
}
.first,
.last {
  width: 49%;
}
@media (max-width: 800px) {
  .first,
  .last {
    width: 100%;
  }
  .send{
      width: 100%!important;
  }
}
</style>
