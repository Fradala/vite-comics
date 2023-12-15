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
                        dc 
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
                        sites
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
                        shop
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
        <div class="container-footer">
           <div class="sing-up">
                <button>
                    sing-up now
                </button>
           </div>
           <div class="follow">
                <p>
                    follow us
                </p>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
           </div>
        </div>

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
        width: 50%;
        flex-wrap: wrap;
        @include flex(row, start, center);

        h3{
            text-transform: uppercase;
        }

        ul{
            list-style-type: none;
        }
    }

}

footer{
    width: 100%;
    background-color: rgb(49, 49, 49);
    padding: 2rem;
    
    .container-footer{
        width: 70%;
        margin: 0 auto;
        @include flex(row, space-between, center);


    button{
            color: white;
            border: 1px solid blue;
            background-color: transparent;
            padding: 10px 20px;
            text-transform: uppercase;
        }


    .follow{
        @include flex(row, center, center);

        p{
            text-transform: uppercase;
            color: rgb(0, 98, 255);
            margin-right: 20px;
        }

        img{
            margin-right: 20px;
        }
    }

    }
}
    
</style>