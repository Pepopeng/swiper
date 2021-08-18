<template>
  <div id="app">
    <swiper>
      <swiperitem><img src="./assets/1.jpeg" alt=""></swiperitem>
      <swiperitem><img src="./assets/2.jpeg" alt=""></swiperitem>
      <swiperitem><img src="./assets/3.jpeg" alt=""></swiperitem>
      <swiperitem><img src="./assets/4.jpeg" alt=""></swiperitem>
    </swiper>

  </div>
</template>

<script>
import swiper from "./components/common/swiper";
import swiperitem from "./components/common/swiperitem";

export default {
  name: 'App',
  components: {
    swiper,swiperitem
  }
}
</script>

<style>
body{
  padding: 0;
  margin: 0;
}
</style>
