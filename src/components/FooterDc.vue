<template lang="">
    <main>
        <section class="info-main-footer">
            <div class="info">
               
                <ul>
                    <h3>
                        dc comics
                    </h3>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                </ul>
                <ul>
                    <h3>
                        dc comics
                    </h3>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                </ul>
                <ul>
                    <h3>
                        dc comics
                    </h3>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                </ul>
                <ul>
                    <h3>
                        dc comics
                    </h3>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                    <li>
                        cose
                    </li>
                </ul>

            </div>
            <div class="dc-logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>

        </section>
        <section class="sub">

        </section>
           
    </main>
    <footer>
        
    </footer>
</template>
<script>

export default {
    name: 'FooterDc',
    
}
</script>
<style lang="scss" scoped>
@use '../styles/partial/variables' as *;
@use '../styles/partial/mixins' as *;

main{
    width: 100%;
    background-image: url(../assets/img/footer-bg.jpg);

    .info-main-footer{
        width: 70%;
        margin: 0 auto;
        
        
        @include flex(row, space-between, center);
    }

    .dc-logo{
        width:50%;
        height: 50%;
        

        img{
            width: 100%;
            height: 100%;
            
        }
        
    }

    .info{
        color: white;
        width: calc(100% / 3);
        flex-wrap: wrap;
        @include flex(row, center, center);

        h3{
            text-transform: uppercase;
        }

        ul{
            list-style-type: none;
        }
    }

}
    
</style>