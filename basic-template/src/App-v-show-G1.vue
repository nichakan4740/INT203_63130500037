<script setup>
const msg = ''
</script>
<template>
  <p>Your Message is {{ msg }}</p>
  <p v-show="!msg" style="color: red" > Please insert your data!</p>

</template>

<style></style>
