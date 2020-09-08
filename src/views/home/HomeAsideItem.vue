<template>
  <div id="HomeAsideItem">
    <icon-base iconName="logo" width="40" height="40" iconColor="#707070"><icon-logo/></icon-base>
  </div>
</template>

<script>
import IconBase from '../../components/IconBase.vue'
import IconLogo from '../../components/icons/IconLogo.vue'
export default {
  name:'HomeAsideItem',
  components:{
    IconBase,
    IconLogo
  }
}
</script>

<style scoped>
#HomeAsideItem{
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  height: 100%;
  flex: 0 0 8rem;
  background-color: white;
}

</style>