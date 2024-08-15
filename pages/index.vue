<script setup lang="ts">
const count = ref(444)
</script>

<template>
  <div>
    <a>Gil</a>
    <strong>{{ count }}</strong>
    <button @click="count++">Increase number + 1</button>
  </div>
</template>
