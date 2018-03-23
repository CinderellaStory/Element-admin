<template>
  <div id="app">
   <Header></Header>
   <LeftNav></LeftNav>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'
import LeftNav from './components/LeftNav'

export default {
  name: 'App',
  components:{
    Header,LeftNav
  }
}
</script>

<style>
*{padding: 0; margin: 0;}
</style>
