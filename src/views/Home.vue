<template>
  <div>
    <Header/>
    <div data-spy="scroll" data-target="#navbar-example2" data-offset="0">
      <Introduction id="index"/>
      <Game id="games"/>
      <AboutUs id="about"/>
    </div>
  </div>
</template>

<script>
import Header from '../components/Header';
import Introduction from '../components/Introduction';
import Game from '../components/Game';
import AboutUs from '../components/AboutUs';

export default {
  name: 'HomePage',
  components: {
    Header,
    Introduction,
    Game,
    AboutUs,
  },
  data () {
    return {
    }
  }
}
</script>

<style>

</style>