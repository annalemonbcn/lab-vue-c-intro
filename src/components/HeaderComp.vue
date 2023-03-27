<template>
  <section id="header">
    <img src="../images/Ironhack_logo.png" alt="ironhack logo">
    <img src="../images/Burger_menu.svg" id="burgerMenu" alt="burger menu icon">
  </section>
</template>

<script>
// No hay import -> No importamos ningún componente
// No hay export -> no hay ninguna variable o método o propiedad o vista a exportar
</script>

<style>
#header{
  padding: 20px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
#header #burgerMenu{
  cursor: pointer;
}
</style>