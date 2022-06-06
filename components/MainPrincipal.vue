<template>
  <main class="mx-8 py-20">
    <section class="mx-auto mt-13 sm:mt-28 container">
      <div>
        <h1 class="text-5xl text-center lg:text-left sm:text-6xl font-bold cor-cinza">
          Cuidando de<br />
          seus Pets
        </h1>
        <p class="py-8 text-center lg:text-left">
          Quem tem filhos peludos sabe o quanto é<br />
          recompensador, refeições e descanso!
        </p>
        <div class="flex gap-5 justify-center lg:justify-start">
          <button class="px-10 py-3 sm:px-14 sm:py-3 font-semibold btn-servicos">Serviços</button>
          <button class="px-10 py-3 sm:px-14 sm:py-3 font-semibold btn-sobre">Sobre nós</button>
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped>
.cor-cinza {
  color: #252525;
}

.btn-servicos {
  background-color: #134c5f;
  border-radius: 20px;
  color: white;
}
.btn-sobre:hover {
  background-color: #b7e2d8;
  border-radius: 20px;
  transition: 0.3s;
}

.container {
  max-width: 1600px;
}
.img-logos {
  height: 40px;
  margin: 20px 40px;
}
</style>
