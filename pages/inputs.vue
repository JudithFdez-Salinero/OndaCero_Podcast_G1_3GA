<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full px-4  z-0 absolute top-0 left-0 h-96" src="../static/svg/Recurso 100.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Inputs, barras y desplegables</h1>
    </div>
    <Title 
    title="Elementos que aumentan su complejidad"
    subtitle="Estos son los inputs, barras de navegación y los desplegables de la aplicación."
    />
    <p class="font-medium w-8/12">
      Estos elementos nos ayudarán en la creación de formularios, de las portadas y la reducción de información.
    </p>
    <div class="ejemplos mb-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-green-400 ">INPUTS</h3>
      <p class=" w-8/12 mb-4">Los inputs tienen variaciones, siendo la más representativa, su variación de error. El resto añaden iconos dentro del input, variando sus funciones. </p>
        <img class="w-full"  src="../static/svg/Recurso 101.svg" alt="primera base">  
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">BARRAS DE NAVEGACIÓN</h3>
      <p class=" w-8/12 mb-4">Estas son las barras de navegación en los dos modos y los dos formatos. Contienen un logotipo,un lista navegable, un buscador y un icono para acceder a tu perfil o el registro. en el caso del móvil, solo iconos.</p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 102.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">BARRAS DE REPRODUCCIÓN</h3>
      <p class=" w-8/12 mb-4">Al igual que en las anteriores, estan en ambos modos y formatos. Cotinienes botones y un reproductor de audio.</p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 103.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">FOOTERS</h3>
      <p class=" w-8/12 mb-4">Funcionan principalmente como un enlace rápido a las redes sociales. Solo existen en el formato web.</p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 104.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">LISTAS</h3>
      <p class=" w-8/12 mb-4">Funcionan para la selección o el marcage de elementos.</p>
           <img class="w-1/2 mr-8"  src="../static/svg/Recurso 105.svg" alt="primera base"> 
    </div>
     <div class="ejemplos mb-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-green-400 ">DESPLEGABLES</h3>
      <p class=" w-8/12 mb-4">Estos elementos se utilizan para no crear páginas con saturación de información, ocultándola hasta su uso. En este caso tenemos distintas variaciones, añadiendo o eliminando el título, la descripción y el icono. Además de su modo claro y oscuro y sus variaciones para móvil. </p>
        <img class="w-full mr-8"  src="../static/svg/Recurso 106.svg" alt="primera base">  
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