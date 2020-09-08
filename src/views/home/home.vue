<template>
  <div id="home">
    <home-aside-item></home-aside-item>
    <home-list-item></home-list-item>
    <home-main-item></home-main-item>
    <home-panel-item></home-panel-item>
  </div>
</template>

<script>
import HomeAsideItem from './HomeAsideItem.vue'
import HomeMainItem from './HomeMainItem.vue'
import HomeListItem from './HomeListItem.vue'
import HomePanelItem from './HomePanelItem.vue'
export default {
  name:'home',
  components:{
    HomeAsideItem,
    HomeMainItem,
    HomeListItem,
    HomePanelItem
  }
}
</script>

<style scoped>
#home{
  width: 100%;
  height: 100%;
  display: flex;
  flex-flow: row nowrap;
  align-items: flex-end;
}


</style>