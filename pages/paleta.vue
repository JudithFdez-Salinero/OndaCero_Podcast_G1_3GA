<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full bg-gray-900 flex justify-start items-start flex-col py-20 px-10">
      <div class="flex justify-start">
        <div>
        <img class="w-60 mr-6" src="../static/svg/Recurso 47.svg" alt="">
        <p class=" w-8/12 mb-4 text-white">#00CC66</p>
        </div>
        <div>
        <img class="w-60 mr-6" src="../static/svg/Recurso 48.svg" alt="">
        <p class=" w-8/12 mb-4 text-white">#F2F2F2</p>
        </div>
        <div>
        <img class="w-60 mr-6" src="../static/svg/Recurso 49.svg" alt="">
        <p class=" w-8/12 mb-4 text-white">#002C35</p>
        </div>
      </div>
      <h1 class="text-5xl font-extrabold my-4 text-gray-100">Paleta</h1>
    </div>
    <Title 
    title="Paleta de color"
    subtitle="En este caso mostramos nuestra paleta y el por qué de la misma"
    />
    <p class="font-medium w-8/12">
        Estos colores buscan la renovación y el acermiento de la marca al "ahora". Más vivos e intensos que los anterioresintentan mostrar la juventud de la nueva línea de podcast de Onda Cero. 
    </p>
    <div class="logotipo my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">VERDES PRINCIPALES</h3>
      <p class=" w-8/12 mb-4">Este es el verde principal de la marca.</p>
        <img class="mr-4"  src="../static/svg/Recurso 57.svg" alt=""> 
        <p class="mt-8">#00CC66    #33D685    #74D6A6    #8DE0B6</p>  
    </div>
    <div class="ejemplos my-4 p-8 w-full">
         <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-green-400">VERDES SECUNDARIOS</h3>
         <p class=" w-8/12 mb-4">En este caso tenemos 2 verdes secundarios que funcionarán en los diferentes modos de la aplicación.</p>  
       <div class="flex justify-start items-start flex-col">
           <img class="  mr-4"  src="../static/svg/Recurso 53.svg" alt=""> 
           <p class="mt-4">Modo noche</p>   
           <p>#B2FF9E    #B9FC5B    #D0FFC4    #E3FFDB</p>
           <img class="  mt-8"  src="../static/svg/Recurso 56.svg" alt="">  
           <p class="mt-4">Modo día</p>   
           <p>#AFFC41   #C0FFB0    #D0FFC4    #E3FFDB</p>   
       </div>
    </div>
    <div class="logotipo my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">NARANJAS</h3>
      <p class=" w-8/12 mb-4">En los naranjas solo encontramos una gama, puesto que son complemetarios.</p>
      <div class="flex justify-start items-start flex-col">
          <img class="mr-4"  src="../static/svg/Recurso 61.svg" alt=""> 
          <p class="mt-8">#F7A278    #F9B593    #F9CEB8    #F9DFD1</p>
      </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-green-400">AZULES</h3>
      <p class=" w-8/12 mb-4">Estos son los dos azules de la paleta, una gama clara y otra oscura.</p>
      <div class="flex justify-start items-start flex-col">
        <img class="  mr-4"  src="../static/svg/Recurso 66.svg" alt=""> 
        <p class="mt-4">Claro</p>   
        <p>#169E84    #31A892    #42C2AB    #5BDBC3</p>
        <img class="  mt-8"  src="../static/svg/Recurso 58.svg" alt="">  
        <p class="mt-4">Oscuro</p>   
        <p>#002C35   #064A58    #086375    #348394</p>   
      </div>
    </div>
    <div class="logotipo my-4 p-8 bg-gray-200 w-full">
        <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-green-400 text-white">GRISES</h3>
        <p class=" w-8/12 mb-4">Las escala de grises, aparece en todo el diseño, sobre todo en los fondos y la tipografía.</p>
        <div class="flex justify-start items-start flex-col">
            <img class="mr-4"  src="../static/svg/Recurso 55.svg" alt=""> 
            <p class="mt-8">#042127    #1B2527    #6B898C    #BDCED4</p>
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