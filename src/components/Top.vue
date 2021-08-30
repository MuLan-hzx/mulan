<template>
  <div id="top">
    <Logo/>
    <Module :items="navList"/>
    <Input/>
    <Account/>
  </div>
</template>

<script>
import Logo from "@/components/top/Logo";
import Module from "@/components/top/Module";
import Input from "@/components/top/Input";
import Account from "@/components/top/Account";
export default {
  name: "Top",
  components: {Account,Input,Module,Logo},
  props:[''],
  data () {
    return {
      navList: [
        {
          id: 1,
          itemName: '首页'
        },
        {
          id: 2,
          itemName: '工作'
        },
        {
          id: 3,
          itemName: '社交'
        },
        {
          id: 4,
          itemName: 'NBA'
        },
        {
          id: 5,
          itemName: '海岛奇兵'
        },
        {
          id: 6,
          itemName: '财务'
        }
      ]
    }
  }
}
</script>
<style scoped>
#top{height: 40px;display:flex;justify-content:space-around;background-color: yellow}
</style>
