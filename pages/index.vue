<script setup lang="ts"></script>

<template>
  <div class="container mx-auto h-full flex items-center justify-center">
    <div class="flex flex-col gap-4">
      <h1 class="text-5xl">Progressly</h1>
      <p class="text-lg">make todos</p>
      <hr />
      <div class="flex gap-4">
        <NuxtLink class="flex-grow bg-gray-200 text-center p-1" to="/auth/login">Login</NuxtLink>
        <NuxtLink class="flex-grow bg-gray-200 text-center p-1" to="/auth/register">Sigup</NuxtLink>
      </div>
    </div>
    <div></div>
  </div>
</template>
