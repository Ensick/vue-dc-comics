<template>
  <div id="app">
    <div class="container">
       <HeaderComp/>
    </div>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'

export default {
  name: 'App',
  components: {

    HeaderComp,

  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

.container{

  width: 70%;
  margin-inline: auto;
}

</style>
