<template>
  <div id="app">
    <el-container>
      <el-aside class="main-aside" ><app-sidebar></app-sidebar></el-aside>
      <el-container>
        <el-header style="background:green">Header</el-header>
        <el-main class="main">
          <router-view/>
        </el-main>
        <el-footer style="background:blue;">Footer</el-footer>
      </el-container>

    </el-container>
  </div>
</template>

<script>
import SideBar from '@/components/SideBar'

export default {
  name: 'App',

  components:{
    'app-sidebar': SideBar
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

p{
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  //margin-top: 60px;
  //background-color: black;
  height: 100%;
  width: 100%;
}

.main{
  height: calc(100vh - 120px);
  overflow-y: scroll;
}

.main-aside {
  min-width: 100px;
}
</style>
