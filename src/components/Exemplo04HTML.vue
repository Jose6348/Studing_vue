<script setup>
    let texto = "<p style=color:red>Aprendendo a diretiva v-html</p>";
</script>

<template>
    <div v-html="texto"></div>

    <div>{{texto}}</div>
</template>