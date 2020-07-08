<template>
  <div id="app" class="app">
    <div>今日数据</div>
    <a-date-picker></a-date-picker>
<!--    <div class="qr-code">-->
<!--      <img :src="imgUrl" />-->
<!--    </div>-->
  </div>
</template>

<script>
export default {
  data() {
    return {
      imgUrl: ''
    }
  },

  // created: function() {
  //   let route = this.$route;
  //   let id = route.query.id;
  //   this.imgUrl = require('./assets/codes/' + id + '.png')
  //   if (navigator.userAgent.match(/(phone|pad|pod|iPhone|iPod|ios|iPad|Android|Mobile|BlackBerry|IEMobile|MQQBrowser|JUC|Fennec|wOSBrowser|BrowserNG|WebOS|Symbian)/i)) {
  //     console.log('mobile')
  //     //移动端CSS
  //     require("./assets/css/mobile.css");
  //   } else {
  //     console.log('pc')
  //     //PC端CSS
  //     require("./assets/css/pc.css");
  //   }
  //
  // }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
  .app {

  }
</style>
