<template>
  <header class="fixed top-0 left-0 bottom-0 p-4 pt-6">
    <div class="logo flex items-center justify-between  mb-8">
      <img class="my-1 mx-2 h-auto w-8"  src="../../static/svg/Recurso 28.svg" alt="logo">
      <h2 class="mx-4 text-white text-2xl font-bold leading-5">ONDA CERO   PODCAST MANUAL</h2>
    </div>
    <div class="navigation mx-2">
      <nav class="vertical_menu text-gray-300">
        <ul class="empezamos">
          <h3 class="text-lg font-bold text-green-300 mt-2 ">Empezamos</h3>
          <li><nuxt-link class="navbar-item " to="/">Nuestras bases</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/figma">Nuestro Figma</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="7pdf">¿Prefieres un PDF?</nuxt-link></li>
        </ul>
        <ul class="basics">
          <h3 class="text-lg font-bold text-green-300 mt-2 ">Básicos</h3>
          <li><nuxt-link class="navbar-item " to="/logotipo">Logotipo</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/paleta">Paleta</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/tipografia">Tipografía</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/layout">Estructura de Layout</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/images">Imágenes</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/aplicaciones">Aplicaciones</nuxt-link></li>
        </ul>
        <ul class="reticulas">
          <h3 class="text-lg font-bold text-green-300 mt-2 ">Retículas</h3>
          <li><nuxt-link class="navbar-item " to="/reticulas">Base</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/aplicacionesreticula">Aplicaciones</nuxt-link></li>
        </ul>
        <ul class="web">
          <h3 class="text-lg font-bold text-green-300 mt-2 ">Web</h3>
          <li><nuxt-link class="navbar-item " to="/iconos">Iconos</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/botones">Botones, badge y checkbox</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/inputs">Inputs, barras y alertas</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/tarjetas">Tarjetas</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="/formularios">Formularios y portada</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="postcss" scoped>
header {
  width: 16rem;
  background-color: #002c35;
}
</style>