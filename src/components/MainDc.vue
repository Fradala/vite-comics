<template lang="">
    <main>
        <ContenutoMainDc/>
    </main>
   
</template>
<script>
import ContenutoMainDc from './ContenutoMainDc.vue';
export default {
    name: 'MainDc',
    components:{
        ContenutoMainDc
    }
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;

main{
    background-color: black;
    padding: 2rem;
}
    
</style>