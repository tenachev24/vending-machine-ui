<template>
  <VendingMachine msg="Vending Machine App"/>
</template>

<script>
import VendingMachine from "@/components/VendingMachine";

export default {
  name: 'App',
  components: {
    VendingMachine
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
