<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main class="flex flex-col min-h-screen justify-between">
    <header class="bg-white drop-shadow p-4 sticky top-0 z-10">
      <div class="my-container flex items-center justify-between">
        <RouterLink to="/">
          <img alt="Vue logo" class="w-32" src="@/assets/medi.webp" />
        </RouterLink>

        <nav class="flex gap-4">
          <RouterLink class="btn-link" to="/">Home</RouterLink>
          <RouterLink class="btn-link" to="/programs">Our Programs</RouterLink>
          <RouterLink class="btn-link" to="/about">About</RouterLink>
          <RouterLink class="btn-link" to="/contact">Contact</RouterLink>
        </nav>
      </div>
    </header>

    <RouterView class="bg-gray-100 flex-1" />
    <footer class="bg-blue-900 text-white text-center py-4">
      <p class="text-center">
        &copy; {{ new Date().getFullYear() }} medi.academy All rights reserved.
      </p>
    </footer>
  </main>
</template>
