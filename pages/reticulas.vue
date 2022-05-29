<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-14  px-10" >
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Bases</h1>
    </div>
    <Title 
    title="Retícula base de la aplicación"
    subtitle="En este caso, mostramos las tres retíclas preparadas para la aplicación responsive."
    />
    <p class="font-medium w-8/12">
        Mostramos sus medidas y sus divisiones.
    </p>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">DESKTOP</h3>
      <p class=" w-8/12 mb-4"> Esta retícula se compone de 12 columnas con un tamaño adaptado al ancho y 1000 filas con un ancho de 8px. </p>
       <div class="flex justify-start items-start flex-col">
           <img class="w-2/3 mr-4"  src="../static/svg/Imagen 1.png" alt="primera base"> 
       </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">TABLET Y MOBILE</h3>
      <div class="flex justify-start items-start">
      <div class="flex justify-start items-start flex-col">
      <p class=" w-8/12 mb-4"> Esta retícula se compone de 8 columnas con un tamaño adaptado al ancho y 1000 filas con un ancho de 8px. </p>
           <img class="w-96 mr-4"  src="../static/svg/Imagen 3.png" alt="primera base"> 
       </div>
      <div class="flex justify-start items-start flex-col">
        <p class=" w-8/12 mb-4"> Esta retícula se compone de 4 columnas con un tamaño adaptado al ancho y 1000 filas con un ancho de 8px. </p>
           <img class="w-32 mr-4"  src="../static/svg/Imagen 2.png" alt="primera base"> 
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