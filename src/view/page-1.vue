<!--
 * @Author: lx000
 * @Date: 2021-11-10 11:38:58
 * @LastEditTime: 2021-11-19 00:38:37
 * @Description: 描述
-->
<script setup lang="ts">
  import Halo from "@/components/halo.vue";
</script>
<template>
  <Container>
    <div>
      <a-page-header
        title="我的角色列表"
        sub-title="服务端存档已同步(自动)" />
        <a-divider style="background-color:#b99d6e;"/>
      <a-list item-layout="horizontal">
        <a-list-item style="border-color:#b99d6e">
          <a-list-item-meta description="召唤亚马逊">
            <template #title>
              <a href="https://www.antdv.com/">mysumama</a>
            </template>
            <template #avatar>
              <a-avatar src="https://joeschmoe.io/api/v1/random" />
            </template>
          </a-list-item-meta>
        </a-list-item>
        <a-list-item style="border-color:#b99d6e">
          <a-list-item-meta description="开荒用电法">
            <template #title>
              <a href="https://www.antdv.com/">dianfa</a>
            </template>
            <template #avatar>
              <a-avatar src="https://joeschmoe.io/api/v1/random" />
            </template>
          </a-list-item-meta>
        </a-list-item>
        <a-list-item style="border-color:#b99d6e">
          <a-list-item-meta description="动物园">
            <template #title>
              <a href="https://www.antdv.com/">druuuuu</a>
            </template>
            <template #avatar>
              <a-avatar src="https://joeschmoe.io/api/v1/random" />
            </template>
          </a-list-item-meta>
        </a-list-item>
      </a-list>
    </div>
  </Container>
</template>
<style scoped>
  .halo {
    z-index: 0;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
</style>
