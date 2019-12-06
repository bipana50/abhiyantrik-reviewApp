<template>
  <div id="container">
  <sidebar></sidebar>
  <sideMain></sideMain>
  </div>
</template>

<script>

import sidebar from './Sidebar.vue'
import sideMain from './SideMain.vue'


export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    'sidebar' : sidebar,
    'sideMain': sideMain
  }
}
</script>

<style lang="scss">

#container {
  /*background-image: url("./assets/bg.png");  */
  height: 100vh;
  width: 100%; 
  /*background-position: center; 
  background-repeat: no-repeat; 
  background-size: cover; */
}


</style>
