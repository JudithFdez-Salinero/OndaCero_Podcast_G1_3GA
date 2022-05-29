<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full px-4  z-0 absolute top-0 left-0 h-96" src="../static/svg/Recurso 108.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Formularios y portada</h1>
    </div>
    <Title 
    title="Mira los formularios y un ejemplo de la portada de Inicio"
    subtitle="Estos son los últimos elementos del sistema de la aplicación y se comforman por los componentes antes mostrados. "
    />
    <p class="font-medium w-8/12">
      Tanto los formularios como la portada son elementos complejos que se conformarían de componentes moleculares.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">FORMULARIOS</h3>
      <p class=" w-8/12 mb-4">Este ejemplo es el de formulario de usuario. Encontrándonos imágenes, botones, texton inputs y links. Tambien en modo día y noche y en formato web y móvil.</p>
        <img class="w-2/3"  src="../static/svg/Group 167.png" alt="primera base">  
    </div>
    <div class="ejemplos my-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">PORTADA</h3>
      <p class=" w-8/12 mb-4">Aquí nos encontramos una barra de navegación, una image, una tarjeta, botones e iconos.</p>
        <img class="w-full mr-8"  src="../static/svg/Headerexample.png" alt="primera base">  
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