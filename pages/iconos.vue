<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full  z-0 absolute top-0 left-0 h-96" src="../static/svg/Recurso 85.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Iconos</h1>
    </div>
    <Title 
    title="Iconos creados a partir del logotipo"
    subtitle="Hemos creado todo un sistema de iconos que se adapta a nuestro diseño."
    />
    <p class="font-medium w-8/12">
       Con ellos podemos mantener el sistema incluso en los elementos más pequeños. Podemos encontrar flechas, hastags, reproductores, redes sociales, etc.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">ICONOS SIN FONDO</h3>
      <p class=" w-8/12 mb-4">Estos son todos los iconos que no tienen fondo y se adaptan a los dos modos de pantalla que diseñamos.</p>
       <div class="flex justify-start items-start flex-col">
           <div class="flex justify-start items-start w-full">
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 86.svg" alt="primera base">  
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 87.svg" alt="primera base"> 
           </div>
           <div class="flex justify-start items-start w-full">
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 88.svg" alt="primera base"> 
           <img class="w-1/6  mr-12 m-8"  src="../static/svg/Recurso 89.svg" alt="primera base"> 
           </div>
        </div>
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">ICONOS CON FONDO</h3>
      <p class=" w-8/12 mb-4">Estos son todos los iconos que  tienen fondo y se adaptan también a los dos modos de pantalla que diseñamos.</p>
       <div class="flex justify-start items-start flex-col">
           <div class="flex justify-start items-start w-full">
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 90.svg" alt="primera base"> 
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 91.svg" alt="primera base"> 
           </div>
           <div class="flex justify-start items-start w-full">
           <img class="w-1/3  mr-12 m-8"  src="../static/svg/Recurso 92.svg" alt="primera base"> 
           <img class="w-1/6  mr-12 m-8"  src="../static/svg/Recurso 93.svg" alt="primera base"> 
           </div>
        </div>
    </div>
</div>

</template>

<script>
import ButtonBase from "~/components/Dsys/ButtonBase.vue";
import Title from "~/components/RepetedElements/Title.vue";
export default {
  components: { ButtonBase, Title },
};
</script>

<style>
</style>