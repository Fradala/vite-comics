<template lang="">
  <HeaderDc/>
  <MainDc/>
  <FooterDc/>
</template>
<script>
import HeaderDc from './components/HeaderDc.vue';
import MainDc from './components/MainDc.vue';
import FooterDc from './components/FooterDc.vue';

export default {
  name: 'App',
  components:{
    HeaderDc,
    MainDc,
    FooterDc
  }
  
}
</script>
<style lang="scss">
  @use './styles/general.scss' as *;
  
</style>