<template>
<div class="account-part">
  <div class="item head"><img src="@/components/img/mulan.jpg"></div>
  <div class="item username">mulan</div>
  <div>退出</div>
</div>
</template>

<script>
export default {
  name: "Account"
}
</script>

<style scoped>
.account-part{display: flex;justify-content: space-between;align-items: center}
img{width: 30px;height: 30px;border-radius: 15px;}
</style>
