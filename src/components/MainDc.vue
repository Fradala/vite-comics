<template lang="">
    <main>
        <article>
            <img src="../assets/img/jumbotron.jpg" alt="">
        </article>
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
    


    img{
        width: 100%;
        height: 200px;
        object-fit: cover;
        object-position: start;
        
    }
}
    
</style>