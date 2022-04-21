<template>
  <div id="app">
    <div class="test">宽度测试占屏幕一半</div>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
}
html {
  font-size: 5vw;
}
.test {
  width: 187.5px;
  height: 24px;
  background: #F5F5F5;
  border-radius: 4px;
  font-size: 12px;
  color: #3B85F5;
}
</style>
