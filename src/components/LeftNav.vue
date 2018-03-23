<template>
  <div class="hello">
   <el-row class="tac">
  <el-col :span="4">
    <el-menu default-active="2" class="el-menu-vertical-demo" @open="handleOpen" @close="handleClose" background-color="#545c64" text-color="#fff" unique-opened="false" active-text-color="#ffd04b">
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>营销</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="1-1">优惠券</el-menu-item>
          <el-menu-item index="1-2">满减活动</el-menu-item>
          <el-menu-item index="1-3">满赠活动</el-menu-item>
          <el-menu-item index="1-4">优惠搭配</el-menu-item>
          <el-menu-item index="1-5">团购</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-submenu index="2">
        <template slot="title">
          <i class="el-icon-document"></i>
          <span>交易</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="1-1">优惠券</el-menu-item>
          <el-menu-item index="1-2">满减活动</el-menu-item>
          <el-menu-item index="1-3">满赠活动</el-menu-item>
          <el-menu-item index="1-4">优惠搭配</el-menu-item>
          <el-menu-item index="1-5">团购</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-submenu index="3">
        <template slot="title">
          <i class="el-icon-setting"></i>
          <span>分销</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="1-1">分销订单</el-menu-item>
          <el-menu-item index="1-2">分销员</el-menu-item>
          <el-menu-item index="1-3">佣金激励设置</el-menu-item>
          <el-menu-item index="1-4">激励佣金管理</el-menu-item>
          <el-menu-item index="1-5">分销等级</el-menu-item>
          <el-menu-item index="1-5">操作日志</el-menu-item>
          <el-menu-item index="1-5">分销员通知</el-menu-item>
          <el-menu-item index="1-5">提现管理</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
      <el-submenu index="4">
        <template slot="title">
          <i class="el-icon-menu"></i>
          <span>会员</span>
        </template>
        <el-menu-item-group>
          <el-menu-item index="1-1">会员管理</el-menu-item>
          <el-menu-item index="1-2">会员等级</el-menu-item>
          <el-menu-item index="1-3">积分营销</el-menu-item>
          <el-menu-item index="1-4">积分记录</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
    </el-menu>
  </el-col>
</el-row>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
      handleOpen(key, keyPath) {
        console.log(key, keyPath);
      },
      handleClose(key, keyPath) {
        console.log(key, keyPath);
      }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.list{
  background: red;height: 100%;
}
</style>
