<script setup lang="ts"></script>
<template>
  <header class="w-full p-6 flex bg-blue-900 items-center gap-x-6 text-white">
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/todo">Todo</NuxtLink>
  </header>
  <main class="w-9/12 mx-auto my-0 h-screen text-center pt-32">
    <slot />
  </main>
</template>
