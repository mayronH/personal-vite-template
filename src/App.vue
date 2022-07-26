<script setup lang="ts"></script>

<template>
  <RouterView />
</template>

<style>
#app {
  display: flex;
  flex-direction: column;
  justify-content: space-between;

  min-height: 100vh;
}

main.content {
  flex: 1;

  width: 100%;

  display: grid;
  place-items: center;

  padding-block: var(--small-size-fluid);
  padding-inline: var(--medium-size-fluid);
}
</style>
