<template>
  <div id="side-main">
    <navbar></navbar>
    <mainWrapper></mainWrapper>
  </div>
</template>

<script>
import navbar from './Nav.vue'
import mainWrapper from './Main.vue'

export default {
  name: 'sideMain',
  data () {
    return {
      msg: 'side-main'
    }
  },
  components: {
    'navbar': navbar,
    'mainWrapper': mainWrapper
  }
}
</script>

<style lang="scss">
  #side-main {
    height: 100vh;
    width: 82.96875%;
    float: right; 
 }

</style>
