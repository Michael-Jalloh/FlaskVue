<template>
  <div id="app">
    <el-container>
      <el-aside width="200px" style="background:red;">Aside</el-aside>
      <el-container>
        <el-header style="background:green">Header</el-header>
        <el-main>
          <router-view/>
        </el-main>
        <el-footer style="background:blue;">Footer</el-footer>
      </el-container>

    </el-container>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body {
  margin: 0;
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
</style>
