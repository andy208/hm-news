<template>
  <div class="app">
    <div class="box">我是一个盒子</div>
    <van-button type="info">信息按钮</van-button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      value: ''
    }
  }
}
</script>
<style>
.box {
  width: 300px;
  height: 300px;
  font-size: 75px;
  background-color: violet;
}
</style>
