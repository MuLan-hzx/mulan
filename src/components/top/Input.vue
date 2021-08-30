<template>
<div id="search-module">
  <div class="item input" placeholder=""><input class="search"/></div>
  <div class="item inputIcon"><button>搜</button></div>
</div>
</template>

<script>
export default {
  name: "Input"
}
</script>

<style scoped>
#search-module{display: flex;justify-content: center;align-items: center;line-height: 40px}
.search{width:400px;height: 27px;}
button{width:32px;height: 32px;line-height: 10px;font-size: 18px;text-align: center}
</style>
