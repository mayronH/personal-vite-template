<script setup lang="ts"></script>
<template>
  <main class="content">
    <h1 class="hello-world">
      Hello World <ph-lightbulb :size="64" weight="light" />
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
