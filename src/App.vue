<template>
  <div id="app">
    <HeaderContent />
   <MainContent />
   <FooterContent/>
   <PicturesContent/>
  </div>
</template>

<script>
import MainContent from './components/MainContent.vue'
import HeaderContent from './components/HeaderContent.vue'
import FooterContent from './components/FooterContent.vue'
import PicturesContent from './components/PicturesContent.vue'
export default {
  name: 'App',
  components: {
    MainContent,
    HeaderContent,
    FooterContent,
    PicturesContent,
  },
}
</script>

<style lang="scss">
$main_color: black;


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $main_color;
  margin-top: 60px;
}
</style>
