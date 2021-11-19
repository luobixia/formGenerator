<template>
  <div>
    <router-view />
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  mounted() {
    // 取消开始的loading加载动画
    const preLoad = document.querySelector('#pre-loader')
    preLoad.style.display = 'none'
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
