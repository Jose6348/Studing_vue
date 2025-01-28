<script setup>
let nome = "alice";
let idade = 25;
let numero1 = 10;
let numero2 = 5;

</script>

<template>
  <p>{{"Olá " + nome + " você tem " + idade + " anos"}}</p>
    <p>{{numero1+numero2}}</p>
</template>