<template>
  <div>
    This page belongs to nuxt-layer
    <div>
      {{ $hello("world") }}
    </div>
  </div>
</template>

<script lang="ts" setup>
const { $hello } = useNuxtApp();
</script>
