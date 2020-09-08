<template>
  <div id="HomeMainItem">
    <home-main-header-item></home-main-header-item>
    
  </div>
</template>

<script>
import HomeMainHeaderItem from './HomeMainHeaderItem.vue'
import HomeMainPlayerItem from './HomeMainPlayerItem.vue'
export default {
  name:'HomeMainItem',
  components:{
    HomeMainHeaderItem,
    HomeMainPlayerItem
  }
}
</script>

<style scoped>
#HomeMainItem{
  height: 100%;
  flex: 1 1 0;
}
  
</style>