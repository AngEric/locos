<template>
  <div>
    <Header/>
    <div data-spy="scroll" data-target="#navbar-example2" data-offset="0">
      <Introduction id="index"/>
      <Game id="games"/>
      <AboutUs id="about"/>
      <Policy id="policy"/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from '../components/Header';
import Introduction from '../components/Introduction';
import Game from '../components/Game';
import AboutUs from '../components/AboutUs';
import Policy from '../components/Policy';
import Footer from '../components/Footer';

export default {
  name: 'HomePage',
  components: {
    Header,
    Introduction,
    Game,
    AboutUs,
    Policy,
    Footer,
  },
  data () {
    return {
    }
  }
}
</script>

<style>

</style>