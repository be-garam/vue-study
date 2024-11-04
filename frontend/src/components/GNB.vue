<!-- src/components/GNB.vue -->
<template>
  <nav class="flex items-center justify-between px-10 py-4 bg-white">
    <div class="flex items-center space-x-4">
      <!-- <img src="logo.png" alt="Logo" class="h-8"> -->
      <router-link to="/" class="gnb-link">Home</router-link>
      <router-link to="/about" class="gnb-link">About</router-link>
      <router-link to="/contact" class="gnb-link">Contact</router-link>
    </div>
    <div class="flex items-center space-x-4">
      <span class="text-gray-600">Welcome</span>
      <button class="px-4 py-2 bg-blue-500 text-white rounded-md hover:bg-blue-600">
        Login
      </button>
    </div>
  </nav>
</template>