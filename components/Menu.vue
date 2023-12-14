<script setup lang="ts"></script>

<template>
  <nav
    class="block w-full py-2 mx-auto bg-white border shadow-md border-white/80 bg-opacity-80 backdrop-blur-2xl backdrop-saturate-200 lg:py-4"
  >
    <div
      class="container flex items-center justify-between mx-auto text-blue-gray-900"
    >
      <slot name="branding" />

      <div class="hidden lg:block">
        <slot name="items" />
      </div>
      <div class="flex items-center gap-x-1">
        <slot name="actions" />
      </div>
    </div>
  </nav>
</template>
