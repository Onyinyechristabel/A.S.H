<script setup lang="ts">
import Button from "./Button.vue";
</script>

<template>
  <section class="hero">
    <div class="video-bg">
      <video class="video_bgg" autoplay muted loop playsinline>
        <source src="/images/animeee.mp4" />
      </video>
    </div>
    <div class="hero_content">
      <div class="hero_firstcontent">
        <h3>VIDEOS</h3>
        <div></div>
        <h3>REPLICAS</h3>
        <div></div>
        <h3>EVENTS</h3>
      </div>
      <h2>
        WE BRING YOUR <br data-desktop />
        WORLD <br data-mobile />
        TO LIFE
      </h2>
      <Button />
    </div>
  </section>
</template>
