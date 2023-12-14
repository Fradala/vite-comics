<template lang="">
  <div>
    
  </div>
</template>
<script>
import HeaderCd from './components/HeaderCd.vue';
import MainCd from './components/MainCd.vue';
import FooterCd from './components/FooterCd.vue';

export default {
  name: 'App',
  components:{
    HeaderCd,
    MainCd,
    FooterCd
  }
  
}
</script>
<style lang="scss">
  @use './styles/general.scss' as *;
  
</style>