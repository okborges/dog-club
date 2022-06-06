<template>
  <div class="flex flex-wrap justify-center mt-20">
    <img class="img-logos" src="../assets/img/logo-1.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-2.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-3.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-4.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-5.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-6.png" alt="" />
    <img class="img-logos" src="../assets/img/logo-7.png" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.img-logos {
  height: 40px;
  margin: 20px 40px;
  filter: grayscale(1);
  opacity: 0.4;
  cursor: pointer;
}
.img-logos:hover {
  filter: grayscale(0);
  opacity: 100%;
}
</style>
