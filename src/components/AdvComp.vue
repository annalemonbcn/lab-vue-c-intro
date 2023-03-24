<template>
  <div class="advantages">
    <SingleAdv />
    <SingleAdv />
    <SingleAdv /> 
  </div>
</template>

<script>
import SingleAdv from './SingleAdv.vue';
export default {
  components: {
    SingleAdv
  }
}
// No hay export -> no hay ninguna variable o método o propiedad o vista a exportar
</script>


<style>
  .advantages{
    background-color: #39B983;
    display: flex;
    flex-flow: row nowrap;
    align-items: flex-start;
    justify-content: space-around;
    padding: 60px 10% 50px;
    gap: 2rem;
  }
  @media screen and (min-width: 1200px){
    .advantages{
      gap: 8rem;
    }
  } 
</style>