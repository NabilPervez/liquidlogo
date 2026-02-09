<script lang="ts" setup>
import LiquidLogo from '@/components/ui/liquid-logo/LiquidLogo.vue';

const imageUrl = "/N.png";
</script>

<template>
  <div class="flex h-screen w-full items-center justify-center bg-black">
    <div class="w-full max-w-4xl px-8">
      <LiquidLogo :image-url="imageUrl" />
    </div>
  </div>
</template>
