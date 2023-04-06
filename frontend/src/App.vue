<script setup lang="ts">
import { RouterView } from 'vue-router';
import SideBar from './components/SideBar.vue';
import HeaderComponent from './components/HeaderComponent.vue';
</script>

<template>
  <div style="display: flex; flex-direction: column; height: 100vh">
    <HeaderComponent />
    <div style="display: flex; height: 100%">
      <SideBar />
      <RouterView />
    </div>
  </div>
</template>
