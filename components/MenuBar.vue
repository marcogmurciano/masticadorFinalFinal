<template>
    <div class="nav_bar flex justify-between align-middle p-2 bg-black text-white fixed w-full">
        <div class="flex justify-start align-top h-6 gap-2 cuerpo mt-2 ml-2 menui cursor-pointer" @click="menuFun()">
            <img src="/W-icon.svg" alt="" class="w-1" />
            <div class="testo">Menu</div>
        </div>
        <img src="/w-oxfam.svg" alt="" class="w-8 fill-white" />
    </div>
    <div class="desplegable flex flex-col gap-3 text-white bg-black absolute top-14 left-4 p-3" v-if="desplegable">
        <div class="manifiesto flex flex-col gap-3" v-if="props.type == dona">
            <NuxtLink to="/Dona" class="item cuerpo">Dona</NuxtLink>
            <NuxtLink to="/" class="item cuerpo">Tu Masticador</NuxtLink>
        </div>
        <div class="dona flex flex-col gap-3"  v-else>
            <NuxtLink to="/" class="item cuerpo">Tu Masticador</NuxtLink>
            <NuxtLink to="/Nosotros" class="item cuerpo">Manifiesto</NuxtLink>
        </div>
        
    </div>
</template>


<script setup>
const props = defineProps({
    type: String,

 })

let desplegable = ref(false)
const menuFun = () => {
    desplegable.value = !desplegable.value;
};

</script>


<style lang="sass" scoped>

</style>