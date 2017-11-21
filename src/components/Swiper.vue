<template>
  <div class="hello">
    <mt-swipe :auto="4000">
      <mt-swipe-item><img src="http://img4.imgtn.bdimg.com/it/u=2750694183,4138033973&fm=200&gp=0.jpg" alt=""></mt-swipe-item>
      <mt-swipe-item>2</mt-swipe-item>
      <mt-swipe-item>3</mt-swipe-item>
    </mt-swipe>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1,
  h2 {
    font-weight: normal;
  }
  
  mt-swipe{
    width:400px;
    height:200px;
  }
  mt-swipe-item{
    width:400px;
    height:200px;
  }
</style>
