<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" mr-6 z-0 absolute h-64 t-0 l-0 " src="../static/svg/Recurso 64.svg" alt="">
        <h1 class="z-10 absolute top-64 left-2/4 text-5xl font-extrabold my-4 text-white">Tipografía</h1>
    </div>
    <Title 
    title="Esta es la guía de tipografía"
    subtitle="Puedes encontrar los distintos niveles tipográficos para app y web. tambien enlaces de descarga a los archivos ttf."
    />
    <p class="font-medium w-8/12">
        Búscamos una tipografía fuerte, consistente pero variable en cuanto a peso. Esto nos ha permitido adaptarla perfectamente a cualquier soporte. 
    </p>
    <div class="logotipo my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-green-400">TIPOGRAFÍA</h3>
      <p class=" w-8/12 mb-4">Puedes descargar la tipografía y probarla.</p> 
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
          <a class="font-bold text-gray-900" href="/static/types/Outfit-Black.ttf" download>Outfit Black</a>
          <img class="w-8" src="/svg/Recurso 70.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Outfit-Bold.ttf" download>Outfit Bold</a>
        <img class="w-8" src="/svg/Recurso 70.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Outfit-Medium.ttf" download>Outfit Medium</a>
        <img class="w-8" src="/svg/Recurso 70.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Outfit-Regular.ttf" download>Outfit Regular</a>
        <img class="w-8" src="/svg/Recurso 70.svg" alt="">
      </div>
        
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
         <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">ESTILOS PARA DESKTOP</h3>
         <p class=" w-8/12 mb-4">Estos son los tamaños y espaciados para la desktop, que se aplicarán a los diferentes elementos de las páginas.</p>  
       <div class="flex justify-start items-start flex-col">
           <img class="w-2/3  mr-4"  src="../static/svg/Recurso 68.svg" alt="text-web"> 
       </div>
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
     <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">ESTILOS PARA MÓVIL</h3>
     <p class=" w-8/12 mb-4">Estos son los tamaños y espaciados para la móvil, que se aplicarán a los diferentes elementos de las páginas</p>
     <div class="flex justify-start items-start flex-col">
         <img class="w-1/2 mr-4"  src="../static/svg/Recurso 69.svg" alt="text-web"> 
     </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-green-400">EJEMPLOS</h3>
      <p class=" w-8/12 mb-4">En este caso se muestra el uso de estos estílos en loq ue posteriormente serán cards dentro de la app. Como se ve, usamos un pequeño desplazamiento en el salto de línea de los titulares, dándo más movimiento a los bloques.</p>
       <div class="flex justify-start items-start flex-col">
     <img class="w-2/3 mr-4"  src="../static/svg/Recurso 71.svg" alt="text-web"> 
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