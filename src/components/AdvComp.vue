<template>
  <div class="advantages">
    <!-- <SingleAdv titleAdv="Titulo de ejemplo" bodyAdv="Esto es un body de ejemplo para probar" /> -->
    <h1>Hello</h1>
    <SingleAdv v-for="advantage in advantages" :key="advantages.id"
    :titleAdv="advantages.title"
    :bodyAdv="advantages.body" />
    <!-- <SingleAdv />  -->
  </div>
</template>

<script>
import SingleAdv from './SingleAdv.vue';
export default {
  data(){
    return {
      advantages: [
        {
          id: 1,
          title: 'Performant',
          body: 'Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.',
          imgSrc: '../images/USP-1.png'
        },
        {
          id: 2,
          title: 'Approachable',
          body: 'Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.',
          imgSrc: '../images/USP-2.png'
        },
        {
          id: 3,
          title: 'Versatile',
          body: 'A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.',
          imgSrc: '../images/USP-3.png'
        }
      ]
    }
  },
  components: {
    SingleAdv
  },
  created(){
    console.log(this.advantages);
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