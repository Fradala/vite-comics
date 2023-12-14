<template lang="">
   <header>
    <section class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo dc">
    </section>
    <nav class="navigation">
        <ul>
           <li v-for="link in navLink" :class="(link.active) ? 'active' : '' ">
                {{ link.content }}
           </li>
        </ul>
    </nav>
   </header>
</template>
<script>
export default {
    name: 'HeaderDc',
    data() {
        return {
            navLink : [
                {
                    content: 'characther',
                    url: '#',
                    active: false,

                },
                {
                    content: 'comix',
                    url: '#',
                    active: true,
                    
                },
                {
                    content: 'charr',
                    url: '#',
                    active: false,

                },
                {
                    content: 'char',
                    url: '#',
                    active: false,

                },
                {
                    content: 'chara',
                    url: '#',
                    active: false,

                },
                {
                    content: 'char',
                    url: '#',
                    active: false,

                },
                {
                    content: 'comix',
                    url: '#',
                    active: false,
                    
                },
                {
                    content: 'char',
                    url: '#',
                    active: false,

                },
                {
                    content: 'charac',
                    url: '#',
                    active: false,

                },
                {
                    content: 'chara',
                    url: '#',
                    active: false,

                },
            ]
        }
    }
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;


header{
    @include flex(row, space-between, center);
    width: 70%;
    margin: 0 auto;
    padding: 20px;

    section.logo{
        width: 40px
    }

   nav.navigation > ul{
        @include flex (row, center, center);
        list-style-type: none;

        li{
            margin-right: 15px;
            text-transform: uppercase;
            font-size: 12px;

            &.active{
                color: rgb(0, 81, 255);
            }
        }

   }

   

    
}


    
</style>