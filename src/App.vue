<script setup>
import { ref, onMounted } from 'vue'

const text = ref("")

onMounted(() => {
  text.value = "テスト"
})
</script>

<template>
  {{  text }}
</template>

<style scoped>
</style>
