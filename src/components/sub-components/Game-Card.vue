<template>
  <b-card
    style="max-width: 20rem;"
    class="mb-2">
    <b-row>
      <b-col class="card-col" cols="12">
        <img class="card-image" :src="getImage(icon)">
      </b-col>
    </b-row>
    <b-row>
      <b-col class="card-col" cols="12">
        <div class="card-name">{{ title }}</div>
      </b-col>
    </b-row>
    <b-row>
      <b-col class="card-col">
        <div>Downloads</div>
        <div class="card-counter">{{ download }}</div>
      </b-col>
      <b-col class="card-col">
        <div>Reviews</div>
        <div class="card-counter">{{ review }}</div>
      </b-col>
    </b-row>
    <b-row>
      <b-col class="card-col" cols="12">
        <a class="card-button" :href="link">
          <img class="card-img-button" src="@/assets/images/googleplay.png">
        </a>
        <!-- <b-button class="card-button" @click="goToPlayStore">
          <img class="card-img-button" src="@/assets/images/googleplay.png">
        </b-button> -->
      </b-col>
    </b-row>
  </b-card>
</template>

<script>
export default {
  name: 'GameCard',
  props: ['title', 'download', 'review', 'icon', 'link'],
  methods: {
    getImage(path) {
      const images = require.context('../../assets/images', false, /\.png$/);
      return images('./' + path + ".png");
    },
    goToPlayStore(e){
      e.preventDefault();
    }
  },
}
</script>

<style lang="scss">
.row {
  margin-top: 12px;
}
.card-col {
  text-align: center;
}
.card-name {
  font-size: 28px;
  font-weight: 500;
}
.card-image {
  width: 100px;
  height: 100px;
}
.card-counter {
  font-size: 22px;
  font-weight: bold;
  color: #160c28;
}
.card-button {
  background-color: transparent !important;
  border-color: transparent !important;
  padding: 0px !important;
  .card-img-button {
    width: 180px;
    height: 70px;
  }
}
.btn:focus {
  outline: none !important;
  box-shadow: none !important;
}
</style>