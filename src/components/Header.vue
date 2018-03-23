<template>
<el-menu
  :default-active="activeIndex2"
  class="el-menu-demo"
  mode="horizontal"
  @select="handleSelect"
  background-color="#545c64"
  text-color="#fff"
  active-text-color="#ffd04b">
  <el-menu-item index="1" class="logo">
    <img :src="logo">    
  </el-menu-item>
  <el-menu-item index="2">营销</el-menu-item>
  <el-menu-item index="3">交易</el-menu-item>
  <el-menu-item index="4">会员</el-menu-item>
  <el-menu-item index="5"><a href="https://www.ele.me" target="_blank">分销</a></el-menu-item>
</el-menu>
</template>
<script>
export default {
  data (){
    return {
    logo:'http://www.dfmeibao.com.cn/static/images/icon2/header_logo.jpg'    
    }
  }
}
</script>

<style scoped>
a{ text-decoration: none; }
.logo 
  img{width: 140px;}
</style>
