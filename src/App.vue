<script>

import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FastLinksComp from './components/FastLinksComp.vue'
import FooterComp from './components/FooterComp.vue'


export default{
    name: "App",
    components: {
      HeaderComp,
      MainComp,
      FastLinksComp,
      FooterComp,
    }
  }

</script>



<template>
  <HeaderComp/>
  <MainComp/>
  <FastLinksComp/>
  <FooterComp/>
</template>



<style lang="scss">
  @use "./style/main.scss" as *;
</style>
