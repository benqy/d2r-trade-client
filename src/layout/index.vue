<!--
 * @Author: lx000
 * @Date: 2021-11-09 15:58:10
 * @LastEditTime: 2021-11-19 11:20:23
 * @Description: 描述
-->
<script setup lang="ts">
  import Sidebar from "./sidebar/sidebar.vue";
  import Nav from "@/layout/nav/nav.vue";
  import Main from "@/layout/main/main.vue";
</script>
<template>
  <div class="layout-wapper h-100vh w-100vw">
    <!-- nav -->
    <Nav />
    <!-- sidebar -->
    <Sidebar />
    <!-- main -->
    <Main />
    // ? 右键菜单
  </div>
</template>
<style>
  .layout-wapper {
    border-radius: 0.5rem /* 8px */;
    color: #333;
    background: #B8A87B;
  }
</style>
