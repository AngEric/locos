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
            <b-button pill class="intro-button">Get Started</b-button>
          </div>
        </b-col>
        <b-col cols="12" md="6">
          <img src="@/assets/images/mockup-1.png" class="intro-image">
        </b-col>
      </b-row>
    </b-container>
  </div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#160c28" fill-opacity="1" d="M0,320L48,288C96,256,192,192,288,170.7C384,149,480,171,576,165.3C672,160,768,128,864,106.7C960,85,1056,75,1152,90.7C1248,107,1344,149,1392,170.7L1440,192L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>
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
  padding: 8px 30px !important;
  color: #160c28 !important;
  background: #efcb68 !important;
}
</style>