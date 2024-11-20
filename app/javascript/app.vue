<template>
  <div id="app">
    <Header/>
    <Homes/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Homes from './components/Home.vue';
export default {
  components: {
      Header,
      Homes,
    },
  data: function () {
    return {
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
