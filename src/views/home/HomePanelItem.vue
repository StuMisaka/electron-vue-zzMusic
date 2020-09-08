<template>
  <div id="HomePanelItem">
    <div class="pink-block"></div>

  </div>
</template>

<script>
export default {
  name:'HomePanelItem'
  
}
</script>

<style  scoped>
#HomePanelItem{
  display: flex;
  flex-flow: row nowrap;
  justify-content: flex-end;
  align-items: center;
  height: 80%;
  flex: 0 0 5rem;
  background-color: #FFF5F4;
  border-top-left-radius: 1rem;
}

.pink-block{
  margin: 0;
  width: 1.8rem;
  height: 50%;
  background-color: #FF7A7B;
  border-top-left-radius: 1rem;
  border-bottom-left-radius: 1rem;
}
</style>