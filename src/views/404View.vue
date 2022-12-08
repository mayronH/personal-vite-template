<script setup lang="ts">
import { Icon } from '@iconify/vue'
</script>

<template>
  <main class="content">
    <div class="message">
      <Icon icon="cil:face-dead" height="128" />
      <h1>404</h1>
      <h2>Page not Found</h2>
    </div>
  </main>
</template>

<style scoped>
h1 {
  font-size: var(--extra-large-size-fluid);
  line-height: var(--extra-large-size-fluid);
}
.message {
  text-align: center;
}
</style>
