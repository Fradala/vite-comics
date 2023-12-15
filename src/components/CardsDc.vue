<template>
    <article>
        <h2>
            carte
        </h2>

    </article>
    
</template>
<script>
export default {
    name: 'CardsDc',
    props: {
        'imageSrc',
        'price',
        'series',
        'type'

    }
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;
    

article{
    
    width: calc((100% / 6) - 20px);
    margin-right: 10px;
    height: 100px;
    border: 2px solid white;
    margin-top: 20px;
}
    
</style>