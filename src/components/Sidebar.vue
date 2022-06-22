<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="sidebar">
    <h2>
      This is a title of the sidebar
    </h2>
  </div>
</template>

<style scoped>
h2 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

</style>
