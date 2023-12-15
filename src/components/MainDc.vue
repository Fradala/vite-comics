<template lang="">
    <main>
        <article>
            <img src="../assets/img/jumbotron.jpg" alt="">
            <p>
                current series
            </p>
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
    
    article{
        position: relative;
    }


    img{
        width: 100%;
        height: 200px;
        object-fit: cover;
        object-position: center;
        
    }

    p{
        position: absolute;
        color: white;
        text-transform: uppercase;
        padding: 10px 20px;
        background-color:rgb(0, 89, 255);
        top: 160px;
        left: 150px;
    }

    
}
    
</style>