<script setup lang="ts">
import { Icon } from '@iconify/vue'
</script>
<template>
  <main class="content">
    <h1 class="hello-world">
      Hello World <Icon icon="ph:lightbulb" height="64" />
    </h1>
  </main>
</template>

<style scoped>
.hello-world {
  display: flex;
  align-items: center;
  gap: var(--small-size-fluid);
}
</style>
