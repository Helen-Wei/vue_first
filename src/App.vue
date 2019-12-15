<template>
  <div id="app">
     <!-- 1.清空根组件App.vue中的html js css 2.删除router.js应用的组件与路由器3.删除views文件夹与components中的HelloWorld.vue组件 -->
    <!-- 路由占位符 -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
</style>
