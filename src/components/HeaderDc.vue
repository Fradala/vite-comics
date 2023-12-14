<template lang="">
   <header>
    <section class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo dc">
    </section>
    <nav class="navigation">
        <ul>
            <li>
                character
            </li>
            <li>
                comix
            </li>
            <li>
                movie
            </li>
            <li>
                tv
            </li>
            <li>
                game
            </li>
            <li>
                collectible
            </li>
            <li>
                videos
            </li>
            <li>
                fans
            </li>
            <li>
                news
            </li>
            <li>
                shop
            </li>
        </ul>
    </nav>
   </header>
</template>
<script>
export default {
    name: 'HeaderDc',
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;


header{
    @include flex(row, space-between, center)

   .navigation 

    
}


    
</style>