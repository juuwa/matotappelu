<script setup></script>

<template>
  <div class="flex justify-center">
    <div class="rounded-lg p-2 bg-slate-400 text-center w-40 border-2">
      <span class="text-white text-2xl">
        <slot name="text"></slot>
      </span>
    </div>
  </div>
</template>