<template>
  <header>
    <div class="hidden sm:block"></div>
    <div class="mx-8">
      <div class="mx-auto py-8 container-header">
        <div class="flex justify-center items-center sm:mt-0 lg:justify-between">
          <NuxtLink to="/" class="logo"><img src="../assets/img/logo.png" alt="logo" width="200" /></NuxtLink>

          <div class="flex space-x-7">
            <nav class="hidden lg:flex">
              <ul class="text-white space-x-6 flex bloquinho">
                <li><NuxtLink to="/" class="p-2">Home</NuxtLink></li>
                <li><a href="#servicos" class="p-2">Serviços</a></li>
                <li><a href="#produtos" class="p-2">Produtos</a></li>
                <li><a href="#clientes" class="p-2">Clientes</a></li>
                <li><a href="#contato" class="p-2">Contato</a></li>
              </ul>
            </nav>
          </div>
        </div>
        <nav class="flex justify-center mt-7 lg:hidden">
          <ul class="text-white gap-3 flex flex-wrap bloquinho font-bold justify-center">
            <li><a href="/">Home</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#produtos">Produtos</a></li>
            <li><a href="#clientes">Clientes</a></li>
            <li><a href="#contato">Contato</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script></script>

<style scoped>
.bloquinho li {
  background-color: #1a6b86;
  padding: 8px 20px;
  border-radius: 6px;
}

.bloquinho li:hover {
  background-color: #138eb8;
  transition: 0.3s;
}

.container-header {
  max-width: 1700px;
}
</style>
