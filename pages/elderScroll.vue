<script setup lang="ts">
import Footer from "~/components/Footer.vue";
</script>

<template>
  <section class="assassin">
    <Header />
    <div class="assassins">
      <div class="assassin_header">
        <div class="assasin_left">
          <h3>Client / Brand</h3>
          <h4>Short 1-line description</h4>
        </div>
        <h3 class="assassin_right">Assassin’s Creed: Shadows</h3>
      </div>
      <video class="video_bgg" autoplay muted loop playsinline>
        <source
          src="https://res.cloudinary.com/dvk4u5mgl/video/upload/v1770833461/AC_Shadows_Case_Study_Video_1_nghzar.mp4"
        />
      </video>
      <div class="assassin_challenges">
        <h3 class="assassin_challenges_left">
          <span class="assassin_span">[</span>THE CHALLENGE<span
            class="assassin_span"
            >]</span
          >
        </h3>
        <h2 class="assassin_challenges_right">
          Bethesda Softworks, the publishers of The Elder Scrolls Online were
          announcing a major expansion that introduced a revolutionary new
          crafting system for players. This system, called "Scribing," centers
          around a unique in-game tool called the "True-Sight Lens," which
          players need to craft and customize unlimited new combat skills to
          suit their playstyle, adding a whole new dimension to gameplay.
          Bethesda wanted to generate significant excitement for this expansion,
          titled Gold Road, but they knew they needed more than just advertising
          to cut through the noise and capture the imagination of both existing
          and potential players.
        </h2>
      </div>
      <div class="assassin_approach">
        <h3 class="assassin_approach_left">
          <span class="assassin_span">[</span>OUR APPROACH<span
            class="assassin_span"
            >]</span
          >
        </h3>
        <h2 class="assassin_approach_right">
          Recognizing the need for a truly immersive and engaging experience, we
          came up with a multi-faceted strategy to vividly realize the expansive
          world of Elder Scrolls Online: Gold Road.
        </h2>
      </div>
      <div class="assassin_images_category">
        <img src="" alt="" />
        <img src="" alt="" />
        <img src="" alt="" />
      </div>
      <div class="assassin_takeaway">
        <h3 class="assassin_takeaway_left">
          <span class="assassin_span">[</span>TAKEAWAYS<span
            class="assassin_span"
            >]</span
          >
        </h3>
        <div class="assassin_takeaway_right">
          <h2>
            We bridge the gap between the virtual and the tangible, creating
            immersive experiences that resonate with gamers.
          </h2>
          <h2>
            We tell stories that capture the imagination and deepen player
            connection.
          </h2>
          <h2>
            We reach the right audience with the right message at the right
            time.
          </h2>
          <h2>
            We drive engagement, generate excitement, and contribute to the
            success of our clients' games.
          </h2>
        </div>
      </div>
      <div class="assassin_related">
        <h2>Related Work</h2>
        <div class="assassin_related_content">
          <div>
            <img src="" alt="" />
            <p>Assassin's Creed: Shadows</p>
          </div>
          <div>
            <img src="" alt="" />
            <p>The Elder Scrolls Online: Gold Road</p>
          </div>
          <div>
            <img src="" alt="" />
            <p>Game of Thrones: Legends</p>
          </div>
        </div>
      </div>
    </div>
    <Contact />
    <Footer />
  </section>
</template>
