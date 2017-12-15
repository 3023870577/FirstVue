<template>
  <div>
    <header class="header">
      <div class="back"><i class="icon"></i></div>
      <div class="search"></div>
      <div class="city">城市</div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Index',
  data () {
    return {
      swiperOption: {
        autoplay: 1000,
        direction: 'horizontal'
      }
    }
  }
}
</script>

<style scoped>
  .header {
    display: flex;
    background: #05bad5;
    color: #fff;
  }
  .back {
    width: .64rem;
    line-height: .86rem;
  }
  .search {
    flex: 1;
    margin: .14rem .18rem;
    background: #fff;
    border-radius: .1rem;
  }
  .city {
    width: 1.14rem;
    line-height: .86rem;
    text-align: center;
  }
  .swiper-img-con {
    width: 100%;
  }
  .swiper-img {
    width: 100%;
  }
</style>

