<template>
  <div class="bg-dog">
    <TheHeader />
    <MainPrincipal />
  </div>
  <Clientes />
  <AboutUs />
  <Missao />
  <Servicos />
  <GaleriaClientes />
  <Contato />
  <TheFooter />
</template>

<script>
export default {};
</script>

<style scoped>
* {
  font-family: 'Poppins', sans-serif;
}
.bg-dog {
  background-image: url(https://i.imgur.com/ls0n8aN.jpg);
  background-repeat: no-repeat;
  background-position: left bottom;
  background-size: cover;
}
</style>
