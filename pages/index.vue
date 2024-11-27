<template>
  <div class="text-red-500">
    Index Page
    <div class="flex gap-4">
      <button @click="setLocale('en')">en</button>
      <button @click="setLocale('vi')">vi</button>
      <p>{{ $t('welcome') }}</p>
    </div>
    <n-button>Default</n-button>
  </div>
</template>

<script setup lang="ts">
const { setLocale } = useI18n()

</script>

<style scoped>

</style>