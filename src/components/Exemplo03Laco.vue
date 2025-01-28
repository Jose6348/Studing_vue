<script setup>
    let nomes = [
        "Alice",
        "Jorge",
        "Manoel",
        "Felipe",
        "André",
    ]
</script>

<template>
    <ul>
        <li v-for="nome in nomes">{{nome}}</li>
    </ul>
</template>