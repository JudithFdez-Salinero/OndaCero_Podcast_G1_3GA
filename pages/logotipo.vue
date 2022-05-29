<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full bg-gray-900 flex justify-start items-start flex-col py-20 px-10">
      <div class="mb-10 flex justify-center items-center">
      <img class="w-60 m-6"  src="../static/svg/Recurso 27.svg" alt="logo">
      <img class="w-60 m-6"  src="../static/svg/Recurso 27.svg" alt="logo">
      <img class="w-60 m-6"  src="../static/svg/Recurso 27.svg" alt="logo">
       </div>
      <h1 class="text-5xl font-extrabold my-4 text-gray-100">Logotipo</h1>
    </div>
    <Title 
    title="Formación del logotipo"
    subtitle="Estas son todas las variaciones del corazón de la marca"
    />
    <p class="font-medium w-8/12">
      En primer lugar te contamos de donde sale la idea de este logo. 
      Cogiendo la unión de la O de onda y el número 0, conseguimos la idea del logo.
      Esta pieza se puede desmontar, en base a una retícula de cuatro modulos y volver a montarse, funcionando como un tetris que forma distintas formas onduladas. 
    </p>
    <div class="logotipo my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">FORMACIÓN</h3>
      <p class=" w-8/12 mb-4">Aquí podemos ver la progresión en la formación del logo.</p>
      <div class="flex justify-center items-center">
        <img class="w-60 mr-4"  src="../static/svg/Recurso 32.svg" alt="logo">   
        <img class="w-60 m-4"  src="../static/svg/Recurso 33.svg" alt="logo">  
        <img class="w-60 m-4"  src="../static/svg/Recurso 34.svg" alt="logo">  
        <img class="w-60 m-4"  src="../static/svg/Recurso 35.svg" alt="logo">   
      </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-green-400">ALGUNAS DE LAS OPCIONES EN LA VARIACIÓN</h3>
      <p class=" w-8/12 mb-4">Según la base, los elemento se van formando, dividiendo y colocando para crear las imágenes. 
          Éstas, gracias a sus formas y colores, convierten a la marca en reconocible a pesar de su variación.</p>  
    <div class="flex justify-start items-center">
     <img class="w-60 mr-6"  src="../static/svg/Recurso 39.svg" alt="logo">
     <img class="w-60 m-6"  src="../static/svg/Recurso 38.svg" alt="logo">
     <img class="w-60 m-6"  src="../static/svg/Recurso 41.svg" alt="logo">
    </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-green-400">LOS LOGOTIPOS PRINCIPALES</h3>
      <p class=" w-8/12 mb-6">A pesar de la cantidad de posibilidades, se utilizarán más usualmente y de forma continua en medios impresos estas dos.</p>  
    <div class="flex justify-start items-center">
        <img class="h-60 mr-6"  src="../static/svg/Recurso 44.svg" alt="">
        <img class="w-60 mr-6" src="../static/svg/Recurso 45.svg" alt="">
    </div>
    </div>
    <div class="logotipo my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">COLORES</h3>
      <p class=" w-8/12 mb-4">Aquí tenemos los tonos utilizados para el logotipo</p>
      <div class="flex justify-start items-center">
          <div>
          <img class="w-60 mr-6" src="../static/svg/Recurso 47.svg" alt="">
          <p class=" w-8/12 mb-4">#00CC66</p>
          </div>
          <div>
          <img class="w-60 mr-6" src="../static/svg/Recurso 48.svg" alt="">
          <p class=" w-8/12 mb-4">#F2F2F2</p>
          </div>
          <div>
          <img class="w-60 mr-6" src="../static/svg/Recurso 49.svg" alt="">
          <p class=" w-8/12 mb-4">#002C35</p>
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