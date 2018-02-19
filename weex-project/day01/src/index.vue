<template>
  <div class="wrapper">
    <!--<image :src="logo" class="logo"></image>-->
    <!--<text class="greeting">The environment is ready!</text>-->
    <!--<text class="message">Now, let's use Vue.js to build your Weex app.</text>-->
    <div class="box1">
      <text>12</text>
    </div>
    <div class="box2">
      <text>34</text>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        //logo: 'https://gw.alicdn.com/tfs/TB1yopEdgoQMeJjy1XaXXcSsFXa-640-302.png',
      }
    }
  }
</script>

<style scoped>
  .wrapper {
    justify-content: center;
    align-items: center;
  }
  .box1 {
    width: 200px;
    height: 200px;
    background-color: red;
    border-width: 10px;
    border-color: black;
    border-style: solid;
  }
  .box2 {
    width: 200px;
    height: 200px;
    background-color: yellow;
  }
  /*.logo {*/
    /*width: 424px;*/
    /*height: 200px;*/
  /*}*/
  /*.greeting {*/
    /*margin-top: 70px;*/
    /*font-size: 50px;*/
    /*color: #41B883;*/
  /*}*/
  /*.message {*/
    /*margin: 30px;*/
    /*font-size: 32px;*/
    /*color: #727272;*/
  /*}*/
</style>
