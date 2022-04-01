<script setup lang="ts">

const RSS_URL = 'https://alfred-rsshub.vercel.app/juejin/category/frontend'

</script>

<template>
  <div>
    <div text-4xl>
      <div i-carbon-campsite inline-block />
    </div>
    <a :href="RSS_URL">
      {{ RSS_URL }}
    </a>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
