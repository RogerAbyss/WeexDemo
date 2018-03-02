<template>
  <div class="wrapper">
    <image :src="logo" class="logo"></image>
    <text class="greeting">Abyss</text>
    <text class="message">Hello Weex!</text>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        logo: 'https://gitee.com/rogerabyss/Assert/raw/master/CI/life.jpg',
      }
    }
  }
</script>

<style scoped>
  .wrapper {
    justify-content: center;
    align-items: center;
  }
  .logo {
    width: 400px;
    height: 400px;
  }
  .greeting {
    margin-top: 70px;
    font-size: 50px;
    color: #41B883;
  }
  .message {
    margin: 30px;
    font-size: 32px;
    color: #727272;
  }
</style>
