<script setup lang="ts">

import LeftImageBox from "@/components/TopViewCompontents/LeftImageBox.vue";
import Stack from '@/components/TopViewCompontents/Stack.vue'
</script>

<template>
  <header class="h-[50vh] flex flex-row pt-10 relative">
    <LeftImageBox class="flex-1 border-r-2 border-amber-300"></LeftImageBox>
    <Stack class="flex-1"></Stack>
    <div class="flex-1">test</div>
  </header>
</template>

<style scoped>

</style>