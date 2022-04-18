<script lang="ts" setup></script>
<template>
  <div id="main" class="main-container w-100vw h-100vh">
    <div class="main-wapper h-100vh">
      <div class="main">
        <router-view v-slot="{ Component, route }">
          <transition :name="route.meta.transition">
            <component :is="Component" :key="route.path" />
          </transition>
        </router-view>
      </div>
    </div>
  </div>
</template>

<style scoped>
  @import "@/assets/style/routerKeyframes.css";

  .main-container {
    padding-left: var(--sidebar-offect-width);
    transition: padding-left 0.5s ease;
  }
  .main-wapper {
    padding: var(--nav-height) /* 28px */;
  }
  .main {
    height: 100%;
    position: relative;
  }
</style>
