<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-2/4 z-0 absolute top-0 left-64 h-96 opacity-60" src="../static/svg/Recurso 94.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Botones, badge y checkbox</h1>
    </div>
    <Title 
    title="Botones, badge y checkbox con todas sus variantes"
    subtitle="Todos estos elementos son partes indispensables del diseño."
    />
    <p class="font-medium w-8/12">
      Los iremos mostrándo en orden para que los podais analizar. Los botones tienes tres variantes principales. Small, medium y large. Dentro de estas encontramos con fondo y con borde. Y luego se van añadiendo elementos que hacen el botón más complejo.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">BOTONES MODO CLARO</h3>
      <p class=" w-8/12 mb-4">Los botones tendrán el verde corporativo principal, en el caso del modo claro.</p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 97.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">BOTONES MODO OSCURO</h3>
      <p class=" w-8/12 mb-4">Los botones tendrán uno de los verdes corporativos secundarios, en el caso del modo oscuro.</p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 98.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400 ">BADGE</h3>
      <p class=" w-10/12 mb-4">Estos elementos pueden aparecer en las etiquetas o hastags, también para mostrar temáticas u otro tipo de indicaciones concretas de un podcast o noticia.
          No escontramos variaciones tanto en línea y fondo, como en la integración de iconos dentro del badge, complejizándose al igual que los botones. También encontraríamos el badge con el icono de cerrar que saldría para quitar esas notificaciones. 
      </p>
           <img class="w-full mr-8"  src="../static/svg/Recurso 99.svg" alt="primera base"> 
    </div>
    <div class="ejemplos my-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400 ">CHECKBOX</h3>
      <p class=" w-10/12 mb-4">Éstos elementos se usarían principalmente dentro de los formularios, para marcar las opciones elegidas. 
      </p>
           <img class="w-1/6 mr-8"  src="../static/svg/Recurso 257.svg" alt="primera base"> 
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