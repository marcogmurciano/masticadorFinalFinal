<template>
    <title>Dona</title>
    <MenuBar type="dona"></MenuBar>
    <div class="p-5">
      <h1 class="p-3 mb-3 text-3xl text-center mt-10">Dona para Masticar</h1>
      <div class="cuerpo text-center mb-3">
        Dona para la fabricación de masticadores en comunidades desfavorecidas,
        Intermon Oxfam está trabajando en diversas comunidades de Sudán del Sur,
        Haití, Afghanistán, Perú, El Congo, Filipinas... Con el dinero donado
        colaboras para la compra de productos de apoyo a la masticación para
        personas que no tienen tanta suerte como tú
      </div>

      <div class="max-w-4xl m-auto">
        <div class="cont flex flex-col align-middle gap-8">
          <div class="card_cont flex gap-4 justify-center">
            <div class="card flex gap-1 flex-col align-middle justify-center">
              <div class="futura text-2xl text-center numerali">68</div>
              <div class="mini max-w-[70px] text-center">Millones Recaudados</div>
            </div>
            <div class="card flex gap-1 flex-col align-middle justify-center">
              <div class="futura text-2xl text-center numerali">93</div>
              <div class="mini max-w-[70px] text-center">Paises Ayudados</div>
            </div>
            <div class="card flex gap-1 flex-col align-middle justify-center">
              <div class="futura text-2xl text-center numerali">03</div>
              <div class="mini max-w-[70px] text-center">Personas Insatisfechas</div>
            </div>
          </div>
          <div class="payment flex justify-center align-middle gap-4 cuerpo">
            <div class="pay">Tarjeta</div>
            <div class="pay">Google Pay</div>
            <div class="pay">PayPal</div>
          </div>
        </div>
      </div>
    </div>
    <img src="/ninio.webp" alt="" class="h-72 object-cover w-full mb-5" />
</template>


<script setup>



</script>


<style lang="sass" scoped>
    .papa
        @apply p-8
    .button
        @apply p-4 rounded-xl text-white
        width: fit-content
        @apply bg-purple-900
</style>