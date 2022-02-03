<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'

</script>

<template>
  <q-header elevated class="bg-primary text-white">
    <q-toolbar>
      <q-toolbar-title>
        <q-avatar>
          <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
        </q-avatar>
        Title
      </q-toolbar-title>

      <q-btn flat :icon="isDark ? 'dark_mode' : 'light_mode'" @click="toggleDark()" />
    </q-toolbar>
  </q-header>
</template>
