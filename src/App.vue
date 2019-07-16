<template>
  <div id="app">
    <Header/>
    <div class="main">
      <Kaiguan/>
      <Zhuangtai/>
      <zhiling/>
    </div>
  </div>
</template>

<script>
import Header from './components/kongzhi/header'
import Kaiguan from './components/kongzhi/switch'
import Zhuangtai from './components/kongzhi/style'
import Zhiling from './components/kongzhi/zhiling'

export default {
  name: 'app',
  components: {
    Header,
    Kaiguan,
    Zhuangtai,
    Zhiling
  }
}
</script>

<style>
  body {
    margin: 0;
    padding: 0;
    background: #f9f9f9;
  }
</style>
