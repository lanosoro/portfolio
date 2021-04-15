<template>
  <div id="app">
    <nav/>
        <router-view/>
  </div>
</template>
<script>
import nav from './components/nav.vue'
export default {
  // eslint-disable-next-line vue/no-unused-components
  components: { nav },
  
}
</script>
<style lang="stylus">
#app 
  padding 0px
  margin 0px
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
  position static


</style>
