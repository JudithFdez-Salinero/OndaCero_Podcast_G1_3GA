<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full  mr-6 z-0 absolute top-0 left-0 h-96" src="../static/svg/Rectangle 154.png" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Tarjetas</h1>
    </div>
    <Title 
    title="Todas las tarjetas utilizadas en la navegación"
    subtitle="Explicamos como se conforman."
    />
    <p class="font-medium w-8/12">
      Estos elementos están formados por una imagen y un texto. en algunas variaciones incluyen un boton. Estos elementos pueden estar inscritos dentro de la porpia imagen o en el exterior de la misma. 
      estas variaciones dan dinamismo en las diferentes composiciones de página, además de ayudar a organizar la información en secciones diferenciadas. Facilitando la lectura de la página. 
      La imagen nos ayuda a distinguir entre podcast sin la necesidad de leer, una vez conozcamos el contenido, relacionando imagen con información.
    </p>
    <div class="ejemplos my-8 p-8 bg-gray-900  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">TARJETAS MODO NOCHE</h3>
      <p class=" w-8/12 mb-4 text-white">Los inputs tienen variaciones, siendo la más representativa, su variación de error. El resto añaden iconos dentro del input, variando sus funciones. </p>
        <img class="w-2/3 mr-8"  src="../static/svg/mosaic_cards.png" alt="primera base">  
        <img class="w-2/3 mr-8"  src="../static/svg/notext_cards.png" alt="primera base">
        <img class="w-3/4 mr-8"  src="../static/svg/outsite_text_button.png" alt="primera base">
        <img class="w-full mr-8"  src="../static/svg/outsite_text_button_lateral.png" alt="primera base">
    </div>
     <div class="ejemplos mb-4 p-8 bg-gray-200  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-green-400 text-white">TARJETAS MODO DÍA</h3>
      <p class=" w-8/12 mb-4">Los inputs tienen variaciones, siendo la más representativa, su variación de error. El resto añaden iconos dentro del input, variando sus funciones. </p>
        <img class="w-2/3 mr-8"  src="../static/svg/mosaic_cards2.png" alt="primera base">  
        <img class="w-2/3 mr-8"  src="../static/svg/notext_cards2.png" alt="primera base">
        <img class="w-3/4 mr-8"  src="../static/svg/Group 165.png" alt="primera base">
        <img class="w-full mr-8"  src="../static/svg/outsite_text_button_lateral2.png" alt="primera base">
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