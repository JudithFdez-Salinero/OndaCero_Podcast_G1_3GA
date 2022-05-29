<template>
  <a :href="href" class="button  w-24 flex justify-center items-center m-1 p-2 bg-green-400 rounded-md">
	<span class="button__text w-20 text-green-50 font-bold">{{text}}</span>
  </a>
</template>

<script>
export default {
  props: {
      text: {type: String}, 
      href: {type: String,}
  }
}
</script>
<style scoped>

</style>