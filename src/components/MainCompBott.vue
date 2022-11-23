<template>
    <div class="main-bott">

        <div>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="img">   
            <span>DIGITAL COMICS</span>              
        </div>

        <div>
            <img src="../assets/img/buy-comics-merchandise.png" alt="img">
            <span>DC MERCHANDISE</span>
        </div>

        <div>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="img">
            <span>SUBSCRIPTION</span>
        </div>

        <div>
            <img class="w-small" src="../assets/img/buy-comics-shop-locator.png" alt="img">
            <span>COMIC SHOP LOCATOR</span>
        </div>

        <div>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="img">
            <span>DC POWER VISA</span>
        </div>
       
    </div>

</template>

<script>
    export default {
        name: 'MainBott',
        
    }
</script>

<style lang="scss" scoped>

    .main-bott{

        width: 68%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-between;

        div{

            cursor: pointer;
            display: flex;
            align-items: center;

            img{
                 width: 60px;
                 height: 75px;
            }

            .w-small{

                width: 50px;
            }

            span{

                font-size: 1.1rem;
                padding-inline-start: 15px;
                color: white;
            }
        }
    }

</style>