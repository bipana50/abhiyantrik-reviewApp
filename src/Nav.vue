<template>
  <div id="navbar">
    <div>Profile</div>
  </div>
</template>

<script>
export default {
  name: 'navbar',
  data () {
    return {
      msg: 'navbar'
    }
  }
}
</script>

<style lang="scss">
#navbar{
  background-color: #C0C0C0;
  width: 100%;
  height: 9.25925925926vh;
}
#navbar div{
  width: fit-content;;
  text-align: left;
  font-family: Lilita One, Regular;
  font-size: 2rem;
  letter-spacing: 0;
  color: #FAFAFA;
  line-height: 9.25925925926vh;
}



</style>
