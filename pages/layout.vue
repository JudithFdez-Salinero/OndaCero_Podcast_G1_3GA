<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full h-80 mr-6 z-0 absolute top-8 left-0 opacity-50" src="../static/svg/Recurso 73.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Layout</h1>
    </div>
    <Title 
    title="Aquí verás como se forma el sistema por el cuál se componen los diferentes elementos."
    subtitle="La base, es el cuadrado, a partir de el sumándole 3 se forma el siguiente y así progresivamente."
    />
    <p class="font-medium w-8/12">
        Ya hemos visto la formación del logo, pero a continuacióm veremos la formación de algunos de los componentes. 
    </p>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-green-400">BASE</h3>
      <p class=" w-8/12 mb-4">Esta sería la base de la que hemos hablado.</p>
       <div class="flex justify-start items-start flex-col">
           <img class="w-2/3  mr-4"  src="../static/svg/Recurso 74.svg" alt="primera base"> 
       </div>
    </div>
     <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">EJEMPLOS Y APLICACIONES</h3>
      <p class=" w-8/12 mb-4">Progresivamente vemos como se forman los distintos elementos, con la suma de estos cuadrados. En este caso, podemos ver los tamaños
          finales. Todos múltiplos de cuatro para adaptarse al formato digital.
      </p>
       <div class="flex justify-start items-start flex-col">
     <img class="w-full mr-4"  src="../static/svg/Recurso 75.svg" alt="text-web"> 
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