<template>
  <div>
    <div class="intro-body">
    <b-container>
      <b-row align-v="center">
        <b-col cols="12" md="6" class="mb-4 mb-md-0">
          <div>
            <div class="intro-title">Locos Creative</div>
            <div class="intro-subtitle">An indie game studio that specialized in simulator game</div>
            <div class="intro-description" style="margin-top:10px; margin-bottom: 18px;">Try our published games &amp; give your feedback</div>
            <div>
              <span><img class="intro-award" src="@/assets/images/award-igc-2017.jpg"></span>
              <span><img class="intro-award" src="@/assets/images/award-googleplay-2017.jpg"></span>
              <span><img class="intro-award" src="@/assets/images/award-gameprime-2017.jpg"></span>
            </div>
            <b-button pill class="intro-button" href="#games">Get Started</b-button>
          </div>
        </b-col>
        <b-col cols="12" md="6">
          <img src="@/assets/images/mockup-1.png" class="intro-image">
        </b-col>
      </b-row>
    </b-container>
  </div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#160c28" fill-opacity="1" d="M0,320L40,272C80,224,160,128,240,96C320,64,400,96,480,112C560,128,640,128,720,112C800,96,880,64,960,90.7C1040,117,1120,203,1200,240C1280,277,1360,267,1400,261.3L1440,256L1440,0L1400,0C1360,0,1280,0,1200,0C1120,0,1040,0,960,0C880,0,800,0,720,0C640,0,560,0,480,0C400,0,320,0,240,0C160,0,80,0,40,0L0,0Z"></path></svg>
  </div>
</template>

<script>
export default {

}
</script>

<style style="scss">
.intro-body {
  background: #160c28;
  padding: 50px 0px;
}

.intro-title {
  font-size: 50px;
  color: #fff;
}

.intro-subtitle {
  font-size: 30px;
  color: #fff;
}

.intro-description {
  font-size: 18px;
  color: rgb(209, 209, 209);
  font-weight: 100;
}

.intro-image {
  display: block;
  max-width: 100%;
  max-height: auto;
}

.intro-button {
  padding: 8px 40px !important;
  color: #160c28 !important;
  background: #efcb68 !important;
  margin-top: 20px;
}

.intro-award {
  border-radius: 10px;
  height: 60px;
  width: 60px;
  margin-right: 20px;
}
</style>