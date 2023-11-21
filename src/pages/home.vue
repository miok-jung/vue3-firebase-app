<template>
  <div>
    <div class="text-h4">Home</div>
    <div>{{ $route.name }}</div>
    <div>{{ $route.meta }}</div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>

<route lang="yaml">
name: home-page
meta:
  requiresAuth: true
</route>
