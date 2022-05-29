<template>
    <div class="elements_container_individual">
        <h3 class="name font-bold text-lg text-gray-900">{{name}}</h3>
        <p class="text text-base font-medium text-gray-900">{{text}}</p> 
    </div>

</template>

<script>
export default {
    props: {
        name: {type: String},
        text: {type: String},
    }
}
</script>

<style>

</style>