<template>
  <div class="antialiased text-white">
    <div class="flex w-full h-screen justify-center items-center">
      <div class="w-full max-w-4xl">
        <h1 class="font-bold text-5xl text-center">
          Amarra o homem, vai ao laboratório e...
        </h1>
        <div class="bg-base-second p-12 rounded-lg shadow-sm w-full mt-10">
          <p class="text-xl font-mono mb-6">
            Você amarra o homem e se dirige ao laboratório. Você entra silenciosamente e consegue chegar ao salão principal, onde você observa aproximadamente umas 10 pessoas. Um passo em falso entrega a sua posição e você é alvejado. Você morreu.
          </p>
          <div class="items-center grid justify-items-center">
            <img class="lg:max-w-xl rounded-xl" src="~/assets/images/gover.png" alt="">
          </div>
          <div class="mt-4 flex justify-center">
            <a class="button mr-2 inline-block bg-base p-5 rounded-full text-base text-white tracking-wide" href="/play/3">Tente novamente</a>
            <a class="button inline-block bg-base p-5 rounded-full text-base text-white tracking-wide" href="/">Voltar ao início</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  label:hover {
    background: var(--base-color);
  }
</style>