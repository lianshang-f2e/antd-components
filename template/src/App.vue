<template>
  <div id="app">
    <my-component></my-component>
  </div>
</template>

<script>
import myComponent from '../src/components/my-component'; // 引入
export default {
  name: 'app',
  data () {
    return {
    }
  },
  components:{ //注册插件
    myComponent
  },
  methods:{
  }
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
</style>