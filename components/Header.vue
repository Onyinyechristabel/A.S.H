<template>
  <header class="header">
    <div>
      <NuxtLink @click="scrollTo('#caseid')" target="_blank">
        <h3 class="header_text">
          <span>WORK</span>
          <span>WORK</span>
        </h3>
      </NuxtLink>
      <NuxtLink @click="scrollTo('#aboutid')" target="_blank">
        <h3 class="header_text">
          <span>ABOUT</span>
          <span>ABOUT</span>
        </h3>
      </NuxtLink>
    </div>
    <NuxtLink href="/" class="header_profile">
      <div class="menuh">
        <img src="/images/artsvg.svg" alt="" />
        <img class="menuimg" data-mobile src="/images/icon2.svg" alt="" />
      </div>
    </NuxtLink>
    <div>
      <NuxtLink @click="scrollTo('#servicesid')" target="_blank">
        <h3 class="header_text">
          <span>SERVICES</span>
          <span>SERVICES</span>
        </h3>
      </NuxtLink>
      <NuxtLink @click="scrollTo('#contactid')" target="_blank">
        <h3 class="header_text">
          <span>CONTACT US</span>
          <span>CONTACT US</span>
        </h3>
      </NuxtLink>
    </div>
    <!-- <div class="header_menu">
      <h3 data-id="work" class="header_menu_text">WORK</h3>
      <h3 data-id="about" class="header_menu_text">ABOUT</h3>
      <h3 data-id="services" class="header_menu_text">SERVICES</h3>
      <h3 data-id="contact" class="header_menu_text">CONTACT</h3>
    </div> -->
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

function scrollTo(id: string) {
  window.lenis.scrollTo(id);
}
</script>
