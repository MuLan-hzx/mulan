<template>
  <div id="logoItem">
    <div class="item logo"><img src="@/assets/logo.png"></div>
    <div class="item siteName"><strong>MULAN</strong></div>
  </div>
</template>

<script>
export default {
  name: "Logo"
}
</script>

<style scoped>
#logoItem{display: flex;justify-content: space-around;align-items: center}
img{width: 40px;height:40px}
</style>
