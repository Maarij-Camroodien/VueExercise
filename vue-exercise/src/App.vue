<template>
  <NavBar/>
  <router-view/>
  <FooterComp/>
</template>

<script>
import NavBar from  '@/components/NavBar.vue'
import FooterComp from '@/components/FooterComp.vue'
export default {
  components: {
    NavBar,
    FooterComp

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
