<template>
  <section class="case" id="caseid">
    <h2>Our Work</h2>
    <div class="case_content">
      <NuxtLink href="/assassin">
        <div
          class="case_one"
          :class="{ active: progress > 0 && progress < 0.3 }"
        >
          <div>
            <h5>Brand</h5>
            <p>UBISOFT</p>
          </div>
          <h3>Assassin's Creed <span class="shadows"> Shadows </span></h3>
          <div class="readmore">
            <img src="/images/k.webp" alt="" class="k" />
            <h4><span>[</span>READ MORE <span>]</span></h4>
          </div>
        </div>
      </NuxtLink>
      <NuxtLink href="/elderScroll">
        <div
          class="case_one"
          :class="{ active: progress > 0.3 && progress < 0.6 }"
        >
          <div>
            <h5>Brand</h5>
            <p>BETHESDA SOFTWORKS</p>
          </div>
          <h3>
            The Elder Scrolls Online:<br />
            <span class="shadows">Gold Road</span>
          </h3>
          <div>
            <img src="/images/m1.webp" alt="" />
            <h4 class="readmore"><span>[</span>READ MORE <span>]</span></h4>
          </div>
        </div>
      </NuxtLink>
      <NuxtLink href="/gameOfThrones">
        <div
          class="case_one"
          :class="{ active: progress > 0.6 && progress < 0.9 }"
        >
          <div>
            <h5>Brand</h5>
            <P>ZYNGA</P>
          </div>
          <h3>Game of Thrones: <span class="shadows"> Legends</span></h3>
          <div>
            <img src="/images/m3.webp" alt="" />
            <h4 class="readmore"><span>[</span>READ MORE <span>]</span></h4>
          </div>
        </div>
      </NuxtLink>
    </div>
  </section>
</template>

<script setup lang="ts">
import gsap from "gsap";
import { ScrollTrigger } from "gsap/all";
const progress = ref(0);
onMounted(() => {
  gsap.registerPlugin(ScrollTrigger);
  ScrollTrigger.create({
    trigger: ".case",
    scrub: true,
    start: "-15% 0%",
    end: "80% 0%",
    animation: gsap
      .timeline({
        onUpdate: function () {
          progress.value = this.progress();
        },
      })
      .to(".case", { y: 0 }),
  });
});
</script>
