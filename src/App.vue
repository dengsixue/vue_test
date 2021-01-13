<template>
  <div id="app">
    <button>{{ message }} </button>
  </div>
</template>

<script>
var vm=new Vue({
  el:'#app',
  data () {
    msg:'我是那妞'
  }
})

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
button{
  width: auto;
  height: 30px;
}

</style>
