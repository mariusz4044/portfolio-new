<script setup lang="ts">
 import LinkedinBox from '@/components/Socials/LinkedinBox.vue'
 import GithubBox from '@/components/Socials/GithubBox.vue'
 import EmailBox from '@/components/Socials/EmailBox.vue'
</script>

<template>
 <div class="h-[100%] flex flex-col items-center">
   <img src="../../assets/images/image-left.jpg" alt="image left" class="w-[80%] h-[80%] relative rounded-[12px] align-middle">
   <div class="relative h-10 flex flex-row items-center w-[80%] mt-2">
    <LinkedinBox />
    <GithubBox />
    <EmailBox />
   </div>
 </div>
</template>

<style scoped>
  img {
    object-fit: cover;
    mix-blend-mode: color-dodge;
  }
</style>