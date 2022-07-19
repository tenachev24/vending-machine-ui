<template>
  <VendingMachineSkeleton msg="Vending Machine App"/>
</template>

<script>
import VendingMachineSkeleton from "@/components/VendingMachineSkeleton";

export default {
  name: 'App',
  components: {
    VendingMachineSkeleton
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
