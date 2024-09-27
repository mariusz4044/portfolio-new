<script lang="ts" setup>

type List = string[];

const list: List = [
  'TypeScript',
  'Js/Css/Html',
  'Vue 3.0',
  'JQuery',
  'Tailwind',
  'I18N',
  'Postman',
  'Websocket/HTTP',
]

</script>

<template>
  <h3>Stack frontend</h3>
  <div class="flex flex-col">
    <label v-for="item in list" :key="item">
      {{item}}
    </label>
  </div>
</template>

<style scoped>

</style>