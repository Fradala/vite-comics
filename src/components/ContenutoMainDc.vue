<template lang="">
    <section class="content">
        <h1>
            -- Contente goes hear 
        </h1>
    </section>
</template>
<script>
export default {
    name: 'ContenutoMainDc',
    data(){
        return {
            listaDc: []
        }
    }
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;
    

section.content{
        margin-left: 100px;
        color: white;
        @include flex(row, start, start)
    }
</style>