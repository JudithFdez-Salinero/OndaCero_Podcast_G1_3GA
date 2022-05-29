<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full  mr-6 z-0 absolute top-0 left-0 h-96" src="../static/svg/suvi2.jpg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Imágenes</h1>
    </div>
    <Title 
    title="Tipos de imágenes para la aplicación"
    subtitle="Estos son los dos tipos de imágenes que tenemos para la aplicación."
    />
    <p class="font-medium w-8/12">
        Podemos encontrarnos con dos tipos de imágenes, en primer lugar las ilustraciones que tendras varios filtros que ayudarán a la integración de la imágen con el fondo. 
        En segundo lugar, las imágenes de los podcasters que serán fotografías de retrato con fondos neutros, a las que se les aplicarán los mismos filtros.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">FILTROS</h3>
      <p class=" w-8/12 mb-4">Estos son los filtros que se aplican a todas las imágenes. En este orden, habría filtro para el modo claro y el oscuro.</p>
       <div class="flex justify-start items-start flex-col">
           <img class="w-full  mr-4"  src="../static/svg/Recurso 76.svg" alt="primera base"> 
       </div>
    </div>
     <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">ILUSTRACIÓN</h3>
      <p class=" w-8/12 mb-4">En este caso hemos elegido el estilo de la artista Suvi suitala, porque es versálitil y redondeado. Tiene ilustraciones tanto en linea, mancha o en ambas. Esto sin perder su identidad.
      </p>
      <div class="flex justify-start items-start flex-col">
       <img class="w-full mr-4"  src="../static/svg/Recurso 79.png" alt="text-web"> 
      </div>
    </div> 
     <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">FOTOGRAFÍA</h3>
      <p class=" w-8/12 mb-4">Las imágenes serán de los podcasters con fondo neutro y las periodísticas se eleirán en función de la información.
      </p>
       <div class="flex justify-start items-start flex-col">
     <img class="w-full mr-4"  src="../static/svg/Recurso 80.png" alt="text-web"> 
    </div>
  </div>
  <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">EJEMPLOS DE APLICACIÓN</h3>
      <p class=" w-8/12 mb-4">Éstos serían los reusltados en la aplicación de los filtros.
      </p>
       <div class="flex justify-start items-start flex-col">
     <img class="w-full mr-4"  src="../static/svg/Recurso 81.png" alt="text-web"> 
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