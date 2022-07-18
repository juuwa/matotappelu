<script setup>
import Button from "@/components/shared/Button.vue"
</script>

<template>
  <div class="bg-zinc-900 h-screen flex flex-col justify-evenly gap-10">
    <div class="self-center">
      <h1 class="text-white text-5xl md:text-8xl mb-20">Matotappelu</h1>
      <Button>
        <template #text>
          Aloita
        </template>
      </Button>
    </div>
    <div class="self-center">
      <a class="text-white" href="https://github.com/juuwa/matotappelu">Github</a>
    </div>
  </div>
</template>