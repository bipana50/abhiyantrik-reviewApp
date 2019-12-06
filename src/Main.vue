<template>
  <div id="main-wrapper">
  </div>
</template>

<script>
export default {
  name: 'mainWrapper',
  data () {
    return {
      msg: 'main-wrapper'
    }
  }
}
</script>

<style lang="scss">
  #main-wrapper {
  background-image: url("./assets/bg.png"); 
  height: 90.68vh;
  width: 100%; 
  //background-position: center; 
  background-repeat: round; 
  background-size: cover;
  float: right;
}

</style>
