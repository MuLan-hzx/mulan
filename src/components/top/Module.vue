<template>
  <div id="modulesItem">
    <div class="item" v-for="(item, index) in items" :key="items[index].id"><b>{{item.itemName}}</b></div>
  </div>
</template>

<script>
export default {
  name: "Module",
  props: ['items']
}
</script>

<style scoped>
#modulesItem{display: flex;justify-content: space-between}
.item{width:70px;color: purple;font-size: 15px;line-height: 40px;}
</style>
