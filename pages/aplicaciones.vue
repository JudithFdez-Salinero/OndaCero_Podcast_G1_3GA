<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-14  px-10" >
        <img class=" mt-8 w-full mr-6 z-0 absolute top-0 left-0 " src="../static/svg/Recurso 82.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Aplicaciones</h1>
    </div>
    <Title 
    title="Otras aplicaciones fuera de la web"
    subtitle="Aquí te mostramos como funciona el sistema aplicado a otros medios."
    />
    <p class="font-medium w-8/12">
        Patrones, cartelería, retícula... y así hasta el infinito.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">PATRONES</h3>
      <p class=" w-8/12 mb-4">Con las piezas fundamentales extraidas de la formación del logo en la retícula se puede crear patrones de todo tipo. En este ejemplo mostramos algunos de ellos.</p>
       <div class="flex justify-start items-start flex-col">
           <img class="w-full  mr-4"  src="../static/svg/Recurso 83.svg" alt="primera base"> 
       </div>
    </div>
     <div class="ejemplos  p-8 w-full ">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">CARTELES</h3>
      <p class=" w-8/12 mb-4">Éstos son ejemplos de cartelería promocional, en este caso del podcast "Más de uno". También colocados en el sistema de retícula por cuadrados.
      </p>
      <div class="flex justify-start items-start flex-col">
       <img class="w-full mr-4"  src="../static/svg/Recurso 84.svg" alt="text-web"> 
      </div>
    </div> 
     <div class="ejemplos  p-8 w-full">
      <h3 class="mb-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-green-400">OTRAS APLICACIONES FíSICAS</h3>
      <p class=" w-8/12 mb-4">Vemos como el sistema pueda aplicarse a producto de merchandising o incluso dentro de los materiales de la radio.
      </p>
      <div class="flex justify-start items-start">
       <div class="flex justify-start items-start flex-col mx-4">
       <p class=" font-bold text-base mb-6">Tazas</p>
       <img class="  h-56  mr-4"  src="../static/svg/Three_White_Mugs_Mockup.png" alt="text-web"> 
       </div>
        <div class="flex justify-start items-start flex-col mx-4">
       <p class=" font-bold text-base mb-6">Tote bag</p>
       <img class=" h-56  mr-4"  src="../static/svg/rm363-s74-c15-mockup-googlefocus.png" alt="text-web"> 
       </div>
        <div class="flex justify-start items-start flex-col mx-4">
       <p class=" font-bold text-base mb-6">Micrófonos</p>
       <img class=" h-56  mr-4"  src="../static/svg/low-frequency-microphones-with-stand-mockup.png" alt="text-web"> 
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