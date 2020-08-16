<template>
  <div class="intro-body">
    <b-container>
      <b-row align-v="center">
        <b-col cols="12" md="6" class="mb-4 mb-md-0">
          <div>
            <div class="intro-title">Locos Creative</div>
            <div class="intro-subtitle">A team of passionate developer and designer</div>
            <div class="intro-description" style="margin-top:10px;">Try our published games &amp; give your feedback</div>
          </div>
        </b-col>
        <b-col cols="12" md="6">
          <img src="@/assets/images/mockup-1.png" class="intro-image">
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>

<style style="scss">

.intro-body {
  background: #160c28;
  padding: 20px 0px;
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
</style>