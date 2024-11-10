<script setup lang="ts">
definePageMeta({
  layout: "dashboard",
});
</script>

<template>
  <div class="">
    <div class="flex items-center gap-4">
      <div>
        <p>Sun, November 10</p>
        <p class="text-6xl text-bold">Hello Rubbie</p>
        <p class="text-2xl text-indigo-400">How are you feeling today</p>
      </div>

      <div class="h-px bg-gray-300 flex-grow" />
      <button class="bg-indigo-200 p-4 text-indigo-600 rounded-md">
        Checkin
      </button>
    </div>

    <!-- sections -->
    <div class="flex gap-2 flex-col flex-grow">
      <div class="flex gap-4">

        <button class="px-3 py-2 bg-gray-200">Personal</button>
        <button class="px-3 py-2 bg-gray-200">+</button>
      </div>
      <!-- todos -->
       <div>
        <!-- calendar -->
        <div class=" h-96 w-96 bg-gray-200"></div>
       </div>
    </div>


  </div>
</template>
