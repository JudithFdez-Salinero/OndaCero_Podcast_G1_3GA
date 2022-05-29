<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-14  px-10" >
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Aplicaciones</h1>
    </div>
    <Title 
    title="Aplicaciones de las retículas"
    subtitle="Estas son las muestra de como se aplica la retícula a la web y el móvil."
    />
    <div class="ejemplos my-4 p-8 w-full">
       <div class="flex justify-start items-start">
           <img class="w-42 mr-4"  src="../static/svg/Imagen 5.png" alt="primera base">
           <img class="w-42 mr-4"  src="../static/svg/Imagen 8.png" alt="primera base">
           <img class="w-1/2 mr-4"  src="../static/svg/Imagen 7.png" alt="primera base">
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