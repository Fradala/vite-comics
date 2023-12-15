<template>
   
    <article>
       <img :src="imageSrc" alt="">
       <p>
            {{ series }}
        </p>

    </article>
   
    
</template>
<script>
export default {
    name: 'CardsDc',
    props: [
        'imageSrc',
        'price',
        'series',
        'type'
    ]
    
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;
    

article{
    
    width: calc((100% / 6) - 20px);
    margin-right: 10px;
    
    
    margin-top: 20px;


    p{
        font-size: 13px;
        text-transform: uppercase ;
    }

    img{
        width: 100%;

        
    }
}
    
</style>