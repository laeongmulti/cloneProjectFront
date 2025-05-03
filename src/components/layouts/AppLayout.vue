<template>
  <div>
    <Header />
    <main>
      <RouterView />
    </main>
    <TabBar />
  </div>
</template>

<script setup lang="ts">
import Header from '@/components/layouts/Header.vue'
import TabBar from '@/components/layouts/TabBar.vue'
</script>
