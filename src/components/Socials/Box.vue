<script lang="ts" setup>

</script>

<template>
  <div class="flex flex-row justify-center items-center cursor-pointer">
    <div class="size-8 icon-social">
      <slot name="image"></slot>
    </div>
    <label class="ml-1 text-lg">
      <slot name="title"></slot>
    </label>
  </div>
</template>

<style scoped>
  img {
    object-fit: cover;
  }
  .icon-social {
    color: var(--green);
    filter: var(--drop-shadow-green);
    -webkit-filter:  var(--drop-shadow-green);
  }

</style>