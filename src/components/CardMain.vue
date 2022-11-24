
<template>

    <div class="cont-card">
        <div class="card">
            <img :src="contenutoCarta.thumb" alt="img">
            <span>{{contenutoCarta.series.toUpperCase()}}</span>
        </div>
    </div>
    
</template>

<script>
    export default {

        name: 'CardMain',

        props: {

            contenutoCarta: Object,
        }
    }
</script>

<style lang="scss" scoped>

    .cont-card{

        width: calc(100% / 6);
        padding: 15px;
        cursor: pointer;

        .card{

        aspect-ratio: 2/1;
        padding-bottom: 25px;

        img{

            padding-bottom: 10px;
            width: 100%;
            display: block;  
            filter: brightness(0.80);

            &:hover{

                filter: brightness(1.20);
            }
        }

        span{
            font-size: 0.8rem;
            color: white;
        }
    }

    }
    
    
</style>