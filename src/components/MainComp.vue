
<template>
    <main>
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

.section-1{

    background-color: rgba(28, 28, 28, 1);
    padding: 80px 0;
}

.section-2{

    background-color: rgba(2, 130, 249, 1);
    padding: 50px 0;
}


</style>