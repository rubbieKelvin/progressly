<script setup lang="ts">
import appConfig from "~/app.config";
</script>

<template>
  <div class="container mx-auto pt-4">
    <!-- header -->
    <div class=" bg-gray-200 flex justify-between p-4 mb-5">
      <div>
        {{ appConfig.title }}
      </div>
      <div>Rubbie</div>
    </div>
    <!-- body -->
    <slot />
  </div>
</template>
