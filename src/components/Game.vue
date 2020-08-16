<template>
  <div class="game-body">
    <b-container>
      <b-row>
        <b-col cols="12">
          <div class="game-title">Published Games</div>
          <div class="game-subtitle">There are 3 android simulator games that you can try in Google Play Store</div>
        </b-col>
      </b-row>
      <b-row style="margin-top: 40px;">
        <b-col 
          cols="12" md="4"
          v-for="(item, idx) in gameList"
          :key="idx"
          :index="item.name"
          class="mb-4 mb-md-0">
          <GameCard 
            :title="item.name"
            :download="item.download"
            :review="item.review"
            :icon="item.icon"
            :link="item.link"/>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import GameCard from './sub-components/Game-Card';
const gameList = [
  {
    name: 'Mobile Bus Simulator',
    download: '10.000.000+',
    review: 297875,
    icon: 'icon-mbs',
    link: 'https://play.google.com/store/apps/details?id=com.Locos.MBS',
  },
  {
    name: 'Mobile Truck Simulator',
    download: '10.000.000+',
    review: 44447,
    icon: 'icon-mts',
    link: 'https://play.google.com/store/apps/details?id=com.Locos.MTS',
  },
  {
    name: 'Telolet Bus Driving',
    download: '10.000.000+',
    review: 91548,
    icon: 'icon-tbd',
    link: 'https://play.google.com/store/apps/details?id=com.Locos.Telolet',
  }
];

export default {
  name: 'GameSection',
  components: {
    GameCard,
  },
  data () {
    return {
      gameList,
    }
  }
}
</script>

<style lang="scss">
.game-body {
  padding: 30px;
}
.game-title {
  font-size: 40px;
  text-align: center;
}
.game-subtitle {
  font-size: 18px;
  text-align: center;
  font-weight: 300;
}
</style>