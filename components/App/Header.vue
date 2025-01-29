<script setup lang="ts"></script>

<template>
  <nav class="bg-gray-900 text-white py-5 border-b border-gray-700">
    <div class="container mx-auto px-4 sm:px-0 py-2 flex flex-col sm:flex-row justify-center gap-3 sm:gap-0 sm:justify-between items-center">
      <NuxtLink to="/"
        class="text-2xl font-medium">Nuxt 3 Blog</NuxtLink>
      <ul class="nav">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/categories">Categories</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contact">contact</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style>
  ul.nav {
    @apply flex gap-5 items-center justify-end;
  }

  ul.nav > li > a {
    @apply text-gray-300 hover:text-gray-50;
  }

  ul.nav > li > a.router-link-active {
    @apply text-blue-300;
  }

</style>
