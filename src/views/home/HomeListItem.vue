<template>
  <div id="HomeListItem">
    <home-list-search-item></home-list-search-item>

  </div>
</template>

<script>
import HomeListSearchItem from './HomeListSearchItem.vue'
export default {
  name:'HomeListItem',
  components:{
    HomeListSearchItem
  }
}
</script>

<style scoped>
#HomeListItem{
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  height: 100%;
  flex: 0 0 18rem;
  background-color: #E1E2F6;
}
</style>