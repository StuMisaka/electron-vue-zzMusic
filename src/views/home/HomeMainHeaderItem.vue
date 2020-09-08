<template>
  <div id="HomeMainHeaderItem">
    <icon-base iconName="user"    width="40" height="40" iconColor="#707070"><icon-user/></icon-base>
    <icon-base iconName="setting" width="40" height="40" iconColor="#707070"><icon-setting/></icon-base>
    <icon-base iconName="skin"    width="40" height="40" iconColor="#707070"><icon-skin/></icon-base>
  </div>
</template>

<script>
import IconBase from '../../components/IconBase.vue'
import IconUser from '../../components/icons/IconUser.vue'
import IconSetting from '../../components/icons/IconSetting.vue'
import IconSkin from '../../components/icons/IconSkin.vue'
export default {
  name:'HomeHeaderItem',
  components:{
    IconBase,
    IconUser,
    IconSetting,
    IconSkin
  }
}
</script>

<style scoped>
#HomeMainHeaderItem{
  width: 100%;
  height: 5rem;
}


</style>