<script setup>
const route = useRoute()
const id = route.params.id
</script>

<template>
  <div>
    <h1>Detail</h1>
    <p>Identificador recibido: {{ id }}</p>
  </div>
</template>