<template>
<div class="product">
    <h2>Товар: {{ title }}</h2>
    <h3>Цена: {{ price }}</h3>
</div>
</template>

<script setup>
  defineProps({
    title: String,
    price: Number
  })
</script>

<style scoped>
  .product {
    border: 1px solid blue;
    padding: 10px;
    margin-bottom: 10px;
  }
</style>