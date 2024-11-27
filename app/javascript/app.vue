<template>
  <div id="app">
    <Header/>
  </div>
  <RouterView />
</template>

<script>
import Header from './components/Header.vue';
export default {
  components: {
      Header
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
