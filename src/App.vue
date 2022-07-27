<template>
  <div id="app">
    <PaymentsComponent/>
  </div>
</template>

<script>
import PaymentsComponent from './components/PaymentsComponent.vue'

export default {
  name: 'App',
  components: {
    PaymentsComponent
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
