<template>
    <title>Tu Masticador</title>
    <div class="top cuerpo overflow-hidden whitespace-nowrap py-4 bg-black text-white absolute z-20">
        <span class="passing_text">
          · X Alpha: sinónimo de elegancia y exclusividad 
          · Durabilidad y calidad definen este distinguido artículo 
          · Masticador X Alpha: diseño vanguardista y funcionalidad única 
          · La sofisticación radica en los detalles meticulosos 
          · Experiencia única respaldada por la exclusividad del producto 
          · Estilo y estatus convergen en el selecto Masticador X Alpha 
          · Placer diario garantizado con este revolucionario producto 
          · Lujo responsable: compromiso ambiental en productos de primera 
          · Equilibrio perfecto entre salud y diseño en cada ejemplar 
          · Durabilidad y calidad son sellos distintivos de este artículo 
          · El masticador fusiona con maestría diseño y funcionalidad 
          · Detalles meticulosos aportan esencia a la esta experiencia inigualable 
          · Innovación notable en el diseño del este masticador 
          · Estilo y estatus se amalgaman en el Masticador X Alpha
          · Placer diario asegurado con el Masticador X Alpha 
          · Lujo responsable: compromiso ambiental en productos de alta calidad 
          · Equilibrio perfecto entre salud y diseño en cada masticador 
          · La exclusiva elegancia de los productos de lujo 
          · Durabilidad y calidad definen este masticador 
          · Detalles meticulosos son la esencia de la sofisticación 
          · Experiencia única gracias a la limitada disponibilidad de productos 
          · Innovación constante en el diseño del moderno masticador 
          · Estilo y estatus se entrelazan en los productos de lujo 
          · Placer diario gracias al masticador, revolucionario en su campo 
          · Lujo responsable: compromiso ambiental en productos de calidad 
          · Equilibrio perfecto entre salud y diseño en el masticador 
          · La elegancia define a los productos de lujo 
          · Durabilidad y calidad, señas de distinción 
          · El masticador combina diseño y funcionalidad 
          · Detalles meticulosos, clave en la sofisticación 
          · Exclusividad marcada por productos limitados 
          · Innovación constante en el diseño del masticador 
          · Estilo y estatus, atributos de los productos de lujo 
          · Placer diario: el masticador redefine la rutina 
          · Lujo responsable: productos de calidad, compromiso ambiental 
          · Equilibrio perfecto: masticador, fusiona salud y diseño 
          · X Alpha: sinónimo de elegancia y exclusividad 
          · Durabilidad y calidad definen este distinguido artículo 
          · Masticador X Alpha: diseño vanguardista y funcionalidad única 
          · La sofisticación radica en los detalles meticulosos 
          · Experiencia única respaldada por la exclusividad del producto 
          · Estilo y estatus convergen en el selecto Masticador X Alpha
          · Placer diario garantizado con este revolucionario producto 
          · Lujo responsable: compromiso ambiental en productos de primera 
          · Equilibrio perfecto entre salud y diseño en cada ejemplar 
          · Durabilidad y calidad son sellos distintivos de este artículo 
          · El masticador fusiona con maestría diseño y funcionalidad 
          · Detalles meticulosos aportan esencia a la esta experiencia inigualable 
          · Innovación notable en el diseño del este masticador 
          · Estilo y estatus se amalgaman en el Masticador X Alpha
          · Placer diario asegurado con el Masticador X Alpha 
          · Lujo responsable: compromiso ambiental en productos de alta calidad 
          · Equilibrio perfecto entre salud y diseño en cada masticador 
          · La exclusiva elegancia de los productos de lujo 
          · Durabilidad y calidad definen este masticador 
          · Detalles meticulosos son la esencia de la sofisticación 
          · Experiencia única gracias a la limitada disponibilidad de productos 
          · Innovación constante en el diseño del moderno masticador 
          · Estilo y estatus se entrelazan en los productos de lujo 
          · Placer diario gracias al masticador, revolucionario en su campo 
          · Lujo responsable: compromiso ambiental en productos de calidad 
          · Equilibrio perfecto entre salud y diseño en el masticador 
          · La elegancia define a los productos de lujo 
          · Durabilidad y calidad, señas de distinción 
          · El masticador combina diseño y funcionalidad 
          · Detalles meticulosos, clave en la sofisticación 
          · Exclusividad marcada por productos limitados 
          · Innovación constante en el diseño del masticador 
          · Estilo y estatus, atributos de los productos de lujo 
          · Placer diario: el masticador redefine la rutina 
          · Lujo responsable: productos de calidad, compromiso ambiental 
          · Equilibrio perfecto: masticador, fusiona salud y diseño 
        </span>
      </div>
      <div class="body">
        <div class="body_left">
            <div class="left_text">
              <h1>Masticador X Alpha</h1>
              <h2 class="soli">Producto solidario</h2>
            </div>
            
              <div class="comp3d">
                <!-- <video class="video" autoplay loop muted controls="false" playsinline src="/video.MP4"></video> -->
              </div>
            
        </div>
        <div class="body_right">
          <div class="right_top">
            <div class="random_bars flex flex-col gap-0.5">
                <div class="bar_container flex flex-col gap-2" v-for="(data, i) in arrayk">
                    <h3 class="text-white mt-2 ml-2">{{arrayNames[i]}}</h3>
                        <div class="bar bg-white rounded-full flex items-center">
                        <div :class= "`inner_bar w${data}percent`"></div>
                    <h3 class="percent">{{data}}%</h3>
                </div>
        </div> 
            </div>
              <div class="buttons">
                
                <NuxtLink to="/Dona" class="boton mini">Dona</NuxtLink>
                <NuxtLink to="/Nosotros" class="boton mini">Manifiesto</NuxtLink>

              </div>
          </div>
          <div class="firma flex justify-between">
              <div></div>
              <img src="/firma.svg" alt="" />
          </div>
          </div>
         
        </div>
      
    
</template>


<script setup>


const generateRandom = () => {
  return Math.floor(Math.random() * (90 - 20 + 1)) + 20;
};

const randomArray = () => {
  return [generateRandom(), generateRandom(), generateRandom()];
};
const arrayk = randomArray();
console.log(arrayk);

const arrayNames = [
  "Atragantamientos evitados",
  "Calorias ahorradas",
  "Tu vida se alarga en un",
];

// const insertBars = () => {
//   const barras = document.querySelector(".random_bars")

//   if (barras == undefined) {
    
//   } else {
//     let html = "";
//   let counter = 0;
//   for (const data of arrayk) {
//     html += `


//         `;
//     counter++;
//   }

//   barras.innerHTML = html;
//   }
// };
// insertBars();

</script>

<style lang="sass" scoped>

    .papa
        @apply p-8
    .button
        @apply p-4 rounded-xl text-white
        width: fit-content
        @apply bg-purple-900


</style>




