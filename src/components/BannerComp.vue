<template>
  <section id="banner">
    <img src="../assets/logo.svg" alt="vue logo" class="logo">
    <h1>Welcome to Vue.js</h1>
    <p>Become a coding ninja with the fastest-growing JavaScript framework</p>
    <button class="btn">Awesome</button>
  </section>
 </template>

<script>
// No hay import -> No importamos ningún componente
// No hay export -> no hay ninguna variable o método o propiedad o vista a exportar
</script>

<style>
  #banner{
    display: flex;
    flex-flow: column nowrap;
    align-items: center;
    justify-content: center;
    color: #2B2F30;
    font-weight: 800;
    padding: 40px 0 65px;
  }
  #banner .logo{
    max-width: 130px;
  }
  #banner h1{
    font-size: 50px;
    line-height: 95px;
    margin-top: 10px;
  }
  #banner p{
    font-size: 14px;
    line-height: 20px;
    margin-top: 30px;
  }
  #banner .btn{
    margin-top: 30px;
    color: #fff;
    background-color: #34495E;
    border-radius: 13px;
    font-size: 14px;
    line-height: 20px;
    padding: 5px 25px;
    border: 0;
    cursor: pointer;
  }
</style>