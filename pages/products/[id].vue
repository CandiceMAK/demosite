<template>
  <div>
    <h2>Product Id</h2>
    <p>{{ id }}</p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style>
</style>