<script setup>
const { data: count } = await useFetch('https://pokeapi.co/api/v2/pokemon/ditto')
</script>

<template>
    <div class="card_box">
        <hiA />
        {{ count }}
    </div>
</template>

<style scoped>
.card_box{
    width: 200px;
    height: 200px;
    background-color: rgb(0, 255, 21);

}
</style>