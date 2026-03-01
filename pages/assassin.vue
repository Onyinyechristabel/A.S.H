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
          Ubisoft, the developer behind the acclaimed Assassin's Creed
          franchise, sought to make some noise at its flagship event, Ubisoft
          Forward, with the promotion of its upcoming release, Assassin's Creed:
          Shadows. This installment dives into the rich history of Japan for the
          first time, and explores a setting that loyal gamers have been asking
          for since the beginning of the franchise. With a passionate fanbase
          and a legacy of immersive, historically-inspired worlds, Ubisoft
          needed a campaign that would not only thrill their core player base
          but also expand its reach to a broader audience
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
          Our plan fused the digital and physical, transforming the historical
          weaponry and artistry of Assassin's Creed: Shadows into something you
          can see and feel.
        </h2>
      </div>
      <div class="assassin_images_category">
        <img src="/images/ASSASIN.webp" alt="" data-desktop />
        <img src="/images/ASSASIN 2.webp" alt="" data-desktop />
        <img src="/images/ASSASIN 3.webp" alt="" data-desktop />
        <img src="/images/ASSASINS.webp" alt="" data-mobile />
        <img src="/images/ASSASINS 2.webp" alt="" data-mobile />
        <img src="/images/ASSASINS 3.webp" alt="" data-mobile />
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
            Live Event Impact: Offered 25+ influencers and 100+ industry leaders
            a hands-on experience, amplifying buzz and exposure.
          </h2>
          <h2>
            Top-Performing Social Content: Videos with Kabuto helmet and Menpo
            mask at forging demonstration accounted for 68% of total views.
            Playful text overlays and attendee interaction also performed well.
          </h2>
          <h2>
            Custom Paid Media Success: Real-time optimizations boosted positive
            engagement. Videos performed exceptionally, delivering significant
            added value and exceeding average views.
          </h2>
          <h2>
            Podcast Value: Strong complementary asset that offered direct
            insights from Ubisoft and a personal, behind-the-scenes perspective.
          </h2>
        </div>
      </div>

      <div class="assassin_related">
        <h2>Related Work</h2>
        <div class="assassin_related_content">
          <NuxtLink href="/assassin">
            <div>
              <img src="/images/r.webp" alt="" />
              <p>Assassin's Creed: Shadows</p>
            </div>
          </NuxtLink>
          <NuxtLink href="/elderScroll">
            <div>
              <img src="/images/m.webp" alt="" />
              <p>The Elder Scrolls Online: Gold Road</p>
            </div>
          </NuxtLink>
          <NuxtLink href="/gameOfThrones">
            <div>
              <img src="/images/d.webp" alt="" />
              <p>Game of Thrones: Legends</p>
            </div>
          </NuxtLink>
        </div>
      </div>
    </div>
    <Contact />
    <Footer />
  </section>
</template>
