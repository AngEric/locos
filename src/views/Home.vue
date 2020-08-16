<template>
  <div>
    <Header/>
    <Introduction/>
    <Game/>
  </div>
</template>

<script>
import Header from '../components/Header';
import Introduction from '../components/Introduction';
import Game from '../components/Game';

export default {
  name: 'HomePage',
  components: {
    Header,
    Introduction,
    Game,
  },
  data () {
    return {
    }
  }
}
</script>

<style>

</style>