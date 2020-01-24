<template>
  <div id="app">
    <h1>Calculator</h1>
   <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'app',
  components: {
    Calculator
  }
}
</script>

<style>
body
{
  background:#999;
}
h1
{
  text-align: center;
  color:black;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-weight: bold;
  background: #eee;
  display: block;
  padding: 30px;
  font-size:50px; 
}
</style>
