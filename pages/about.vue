<script setup lang="ts">
import { ref } from "vue"

const route = ref(useRoute())
console.log(route)

</script>

<template>
  <h1>Routing</h1>
  <div>
    routeオブジェクト: {{ route }}
  </div>
</template>