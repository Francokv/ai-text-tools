<template>
  <textarea
    v-model="text"
    placeholder="Type something here"
    class="w-full h-32 p-2 border border-gray-300 rounded-lg"
  >

  </textarea>
</template>

<script setup>
const text = ref('hola')
</script>