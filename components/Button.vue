<template>
  <section class="button">
    <NuxtLink href="/contacts" target="_blank">
      <button class="btn bd">LET’S COLLABORATE</button>
      <div class="colors">
        <div></div>
        <div></div>
        <div></div>
      </div>
    </NuxtLink>
  </section>
</template>

<script setup lang="ts">
function scrollTo(id: string) {
  window.lenis.scrollTo(id);
}
</script>
