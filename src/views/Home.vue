<template>
  <div>
    <Header/>
    <Introduction/>
  </div>
</template>

<script>
import Header from '../components/Header';
import Introduction from '../components/Introduction';

export default {
  name: 'HomePage',
  components: {
    Header,
    Introduction,
  },
  data () {
    return {
    }
  }
}
</script>

<style>

</style>