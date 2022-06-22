<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Bienvenue from '@/components/Bienvenue.vue'
import Sidebar from '@/components/Sidebar.vue'
</script>

<template>
  <Sidebar msg="test">
  </Sidebar>
  <Bienvenue msg="test" />

</template>

<style>
</style>
