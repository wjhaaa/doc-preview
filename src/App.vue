<template>
  <div id="app">
    <p style="color:red;">点击下面文件名预览，目前支持['doc', 'docx', 'xls', 'xlsx', 'pdf', 'png', 'jpg', 'jpeg', 'gif']的文件</p>
    <router-view/>
  </div>
</template>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
