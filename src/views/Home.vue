<template>
  <div class="home">
    <img class="logo" alt="Vue logo" src="../assets/logo.png">
    <Calculator />
  </div>
</template>

<script>

import Calculator from "../components/Calculator.vue"

export default {
  name: 'Home',
  components: {
    Calculator
  }
}
</script>
