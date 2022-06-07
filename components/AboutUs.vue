<template>
  <section class="mx-auto container my-12" id="sobre">
    <div class="flex items-center mx-8 justify-around">
      <div class="max-w-lg bg-patinha">
        <p class="sobre">SOBRE NÓS</p>
        <h2 class="text-4xl font-bold my-8">
          Os Pets vivem o dia,<br />
          a hora, cada momento !
        </h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid doloremque non harum voluptas excepturi
          molestias delectus voluptates modi recusandae magnam reiciendis expedita porro maxime iure eius corporis,
          tempora iusto autem?
        </p>
        <div class="mt-8">
          <a href="#TheContato" class="py-3 px-6 btn-servicos font-semibold">Entre em Contato</a>
        </div>
      </div>
      <img class="hidden md:flex" src="https://i.imgur.com/Hb12Fc6.png" alt="" width="400" />
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  max-width: 1600px;
}
.sobre {
  color: #134c5f;
}
.btn-servicos {
  background-color: #134c5f;
  border-radius: 20px;
  color: white;
}


.bg-patinha {
  background-image: url(https://i.imgur.com/frs46sx.png);
  background-size: 600px;
  background-repeat: no-repeat;
  background-position-x: 320px;
}
</style>
