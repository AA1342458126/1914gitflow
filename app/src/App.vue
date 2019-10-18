<template>
  <div id="app">
    这里是1914git测试
    <!--lry-->
    <h3>路人乙：会员注册</h3>
    <input type="text" placeholder="请输入用户名">
    <input type="password" placeholder="请输入密码"><br/>
    <button class="reg-btn">注册</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
  .reg-btn{margin-top: 10px}
</style>
