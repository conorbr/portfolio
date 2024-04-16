<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center mt-5x">
      <div>
        <NuxtLink to="/" class="text-xl font-semi-bold p-2 hover:bg-gray-200">
          Conor Breen
        </NuxtLink>
      </div>

      <Menu />
    </header>

    <main>
      <slot />
    </main>
  </div>
</template>

<script setup>
useHead({
  titleTemplate: "%s - Conor's Blog",
});
</script>
