<template>
  <header class="header">
    <div>
      <NuxtLink href="/" target="_blank">
        <h3 class="header_text">
          <span>WORK</span>
          <span>WORK</span>
        </h3>
      </NuxtLink>
      <h3 class="header_text">
        <span>ABOUT</span>
        <span>ABOUT</span>
      </h3>
    </div>
    <NuxtLink href="/" class="header_profile">
      <div class="menuh">
        <img src="/images/artsvg.svg" alt="" />
        <img class="menuimg" data-mobile src="/images/icon2.svg" alt="" />
      </div>
    </NuxtLink>
    <div>
      <h3 class="header_text">
        <span>SERVICES</span>
        <span>SERVICES</span>
      </h3>
      <h3 class="header_text">
        <span>CONTACT US</span>
        <span>CONTACT US</span>
      </h3>
    </div>
  </header>
</template>

<script setup lang="ts">
import gsap from "gsap";
import { ScrollTrigger } from "gsap/all";
onMounted(() => {
  gsap.registerPlugin(ScrollTrigger);
  ScrollTrigger.create({
    trigger: ".hero",
    scrub: true,
    start: "0% 0%",
    end: "150% 0%",
    animation: gsap.fromTo(
      ".header",
      { backgroundColor: "#00000000" },
      { backgroundColor: "black" },
    ),
  });
});
</script>
