<template>
  <div>
    <span>Hello</span>
<!--    <NuxtRouteAnnouncer />-->
<!--    <NuxtWelcome />-->
  </div>
</template>

<script setup lang="ts">
import "~/assets/styles/main.css"
const counter = ref(0)
console.log('Setup')
onMounted(() => {
  console.log('onMounted')
})

</script>