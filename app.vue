<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">

const { result, search } = useSearch('irrelivant')
const facet = { 
    name: 'category',
    query: 'phone'
   }
  await search({ facet })
</script>