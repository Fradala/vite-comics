<template lang="">
    <footer>
        <infoFooter/>     
    </footer>
</template>
<script>
import infoFooter from './infoFooter.vue';
export default {
    name: 'FooterDc',
    components:{
        infoFooter
    }
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;


    
</style>