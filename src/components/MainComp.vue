
<template>
    <main>
        <div class="jumbo">
            <span class="btn-jumbo">
                CURRENT SERIES
            </span>
        </div>

        <div class="section-1">
            <MainTop/>
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

        .btn-jumbo{

            background-color: rgba(2, 130, 249, 1);
            color: white;
            padding: 15px;
            font-weight: bold;
            cursor: pointer;
            position: absolute;
            bottom: -6%;
            left: 20%;
        }
    }

.section-1{

    background-color: rgba(28, 28, 28, 1);
    padding: 80px 0;
}

.section-2{

    background-color: rgba(2, 130, 249, 1);
    padding: 50px 0;
}


</style>