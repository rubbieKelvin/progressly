<script setup lang="ts"></script>

<template>
  <div class="container mx-auto h-full flex items-center justify-center">
    <div class="flex flex-col gap-4">
      <h1 class="text-3xl">Login</h1>
      <p class="text-lg">signin</p>
      <hr />
      <div class="flex gap-2">
        <input type="text" />
        <input type="password" />
      </div>
      <hr />
      <div class="flex gap-4">
        <NuxtLink class="flex-grow bg-gray-200 text-center p-1" to="/home">
          GO
        </NuxtLink>
      </div>
    </div>
    <div></div>
  </div>
</template>
