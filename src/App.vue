<template>
  <div id="app">
    <div class="row">
      <div class="col-6">
          <img src="./assets/1.jpg" alt="" srcset="">
        <CsButton/>
      </div>
      <div class="col-6">
        <img src="./assets/3.jpg" alt="" srcset="">
        <CsButton/>
      </div>
    </div>
    
  </div>
</template>

<script>
import CsButton from './components/CsButton.vue'

export default {
  name: 'App',
  components: {
    CsButton
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
