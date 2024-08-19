<script setup>
  
  const count = ref(3)
  const double = computed(() => count.value * 2)
</script>

<template>
  <div>
    <p>Count: {{ double }}</p>
    <button @click="count++">Increment</button>
  </div>
</template>