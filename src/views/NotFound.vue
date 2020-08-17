<template>
  <div class="body-404">
    <vue-particles 
        color="#dedede"
        :bg="true">
    </vue-particles>
    <div id="content-404">
      <div class="text-404">404</div>
      <div class="sub-text-404">What are you doing here, buddy?</div>
      <div class="description-404">It looks like you're lost..</div>
      <b-button pill class="button-404" @click="goToHome">Take me back</b-button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NotFoundPage',
  data () {
    return {
    }
  },
  methods: {
    goToHome() {
      this.$router.push({ path: `/`});
    },
  },
}
</script>

<style lang="scss">
$color-primary: #160c28;
$color-secondary: #efcb68;

.body-404 {
  background: $color-primary !important;
}

#particles-js {
  height: 100vh;
}

#content-404 { 
  position: fixed;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.text-404 {
  color: rgba($color-secondary, 0.8);
  font-size: 200px;
}
.sub-text-404 {
  color: rgba($color-secondary, 0.8);
  font-size: 25px;
  font-weight: bold;
  margin-top: -10px;
  margin-bottom: 10px;
}
.description-404 {
  color: rgba($color-secondary, 0.8);
  font-size: 22px;
  font-weight: normal;
}
.button-404 {
  margin-top: 20px;
  padding: 8px 30px !important;
  color: $color-primary !important;
  background: #ffffff !important;
}
</style>