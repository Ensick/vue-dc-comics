
<template>
    <main>
        <div class="jumbo">
            <span class="label-jumbo">
                CURRENT SERIES
            </span>
        </div>

        <div class="section-1">

            <MainTop/>
            <div class="cont-button">
                <span class="btn-blue">LOAD MORE</span>
            </div>
            

        </div>

        <div class="section-2">
            <MainBott/>
        </div>
    </main>
</template>

<script>
import MainTop from './MainCompTop.vue'
import MainBott from './MainCompBott.vue'

    export default {
        name: 'MainComp',

        components:{

            MainTop,
            MainBott,

        }
    }
</script>

<style lang="scss" scoped>

 .jumbo{

    background-image: url('../assets/img/jumbotron.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    height: 400px;
    position: relative;

    .label-jumbo{

        background-color: rgba(2, 130, 249, 1);
        color: white;
        padding: 15px;
        font-weight: bold;
        filter: brightness(0.80);
        position: absolute;
        bottom: -6%;
        left: 20%;
    }
}

 .btn-blue{

    background-color: rgba(2, 130, 249, 1);
    color: white;
    padding: 15px;
    font-weight: bold;
    cursor: pointer;
    filter: brightness(0.80);

    &:hover{

        filter: brightness(1.10);
    }
}

.section-1{

    background-color: rgba(28, 28, 28, 1);
    padding: 80px 0;

    .cont-button{

        width: 70%;
        margin-inline: auto;
        text-align: center;

        span{

            margin: 0 auto;
        }
    }
    
}

.section-2{

    background-color: rgba(2, 130, 249, 1);
    padding: 50px 0;
}


</style>