<template>
  <HeaderComp />
  <BannerComp />
  <AdvComp />
</template>

<!-- OPTIONS API -->
<script>
import HeaderComp from './components/HeaderComp.vue';
import BannerComp from './components/BannerComp.vue';
import AdvComp  from './components/AdvComp.vue'; 
export default {
  components: {
    HeaderComp,
    BannerComp,
    AdvComp,
  }
}
</script>

<!-- COMPOSITION API -->
<!-- <script setup>
import HeaderComp from './components/HeaderComp.vue';
</script> -->

<style scoped>

</style>