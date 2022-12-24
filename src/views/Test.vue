<template>
  <div class="left"></div>
  <div class="right">
    <div class="board">
      <p>呃随便写点啥吧。测试点英文。</p>
      <p>This paragraph is in English.</p>
      <p class="empty"></p>
      <p>测试一下换行的功能，所以这一段要写得长一点特别特别长才会有换行的效果出现。还不够长那我就再加一点吧现在怎么样呢？</p>
    </div>
  </div>


</template>

<script setup>

</script>


<style lang="scss" scoped>
.board {
  background-color: #333;
  width: 480px;
  font-size: 16px;
  padding: 36px;
  margin: 20px auto 0;
}
p {
  text-indent: 32px;
}
p.empty {
  height: 20px;
}
</style>