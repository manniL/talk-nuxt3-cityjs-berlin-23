<script setup lang="ts">
const { data } = await useFetch('/api/conf')
</script>

<template>
  <div class="container">
    <h1>Let's go!</h1>
    {{ data }}
  </div>
</template>