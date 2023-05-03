<script>

import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FastLinksComp from './components/FastLinksComp.vue'


export default{
    name: "App",
    components: {
      HeaderComp,
      MainComp,
      FastLinksComp,
    }
  }

</script>



<template>
  <HeaderComp/>
  <MainComp/>
  <FastLinksComp/>
</template>



<style lang="scss">
  @use "./style/main.scss" as *;
</style>
