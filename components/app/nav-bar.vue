<script setup lang="ts">
import AuthButton from "../auth-button.vue";
</script>

<template>
  <div class="navbar bg-primary text-primary-content">
    <NuxtLink to="/" class="btn btn-ghost navbar-start  text-xl">
      Travel Log
    </NuxtLink>
    <div class="navbar-end">
      <AppThemeToggle />
      <AuthButton />
    </div>
  </div>
</template>
