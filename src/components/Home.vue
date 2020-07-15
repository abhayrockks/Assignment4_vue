<template>
  <c-card>
    <template v-slot:header>
      <img src="../assets/logo.png" />
    </template>

    <template v-slot:title>
      <h2>Card Title</h2>
    </template>

    <template v-slot:body>
      <p>This is the body of the card</p>
    </template>

    <template v-slot:footer>
      <button>Go Somewhere</button>
    </template>
  </c-card>
</template>

<script>
import Card from "./Card";
export default {
  components: {
    "c-card": Card
  }
};
</script>

<style scoped>
</style>