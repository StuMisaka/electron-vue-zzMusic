<template>
  <div id="app">
    <router-link to='/'></router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}
#app{
  margin: 0;
  padding: 0;
  width: 100vw;
  height: 100vh;
}
</style>
