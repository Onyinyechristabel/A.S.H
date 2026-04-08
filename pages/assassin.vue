<template>
  <section class="assassin">
    <Header />
    <div class="assassins">
      <div class="assassin_header">
        <div class="assasin_left">
          <h3>Brand</h3>
          <p>UBISOFT</p>
        </div>
        <h3 class="assassin_right">Assassin's Creed Shadows</h3>
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
          Forward, with the promotion of its upcoming release, Assassin's Creed
          Shadows.
          <br />
          <br />
          This installment dives into Japan's rich history for the first time
          and explores a setting that loyal gamers have been asking for since
          the franchise began. With a passionate fanbase and a legacy of
          immersive, historically inspired worlds, Ubisoft needed a campaign
          that would not only thrill its core player base but also expand its
          reach to a broader audience.
        </h2>
      </div>
      <div class="assassin_approach">
        <h3 class="assassin_approach_left">
          <span class="assassin_span">[</span>OUR APPROACH<span
            class="assassin_span"
            >]</span
          >
        </h3>
        <div class="assassin_approach_righter">
          <h2 class="assassin_approach_right">
            Our plan fused the digital and physical, transforming the historical
            weaponry and artistry of Assassin's Creed: Shadows into something
            you can see and feel.
          </h2>
          <div class="assassin_process">
            <div>
              <h3>1</h3>
              <h2>Sample process one</h2>
            </div>
            <div>
              <h3>2</h3>
              <h2>Sample process one</h2>
            </div>
            <div>
              <h3>3</h3>
              <h2>Sample process one</h2>
            </div>
          </div>
        </div>
      </div>
      <div class="assassin_images_category">
        <img src="/images/ASSASIN.webp" alt="" data-desktop />
        <img src="/images/ASSASIN 2.webp" alt="" data-desktop />
        <img src="/images/ASSASIN 3.webp" alt="" data-desktop />
        <img src="/images/ASSASINS.webp" alt="" data-mobile />
        <img src="/images/ASSASINS 2.webp" alt="" data-mobile />
        <img src="/images/ASSASINS 3.webp" alt="" data-mobile />
      </div>

      <div class="assassin_related">
        <h2>Related Work</h2>
        <div class="assassin_related_content">
          <NuxtLink href="/assassin" class="assassin_related_content_div">
            <img src="/images/r.webp" alt="" />
            <p>Assassin's Creed: Shadows</p>
          </NuxtLink>
          <NuxtLink href="/elderScroll" class="assassin_related_content_div">
            <img src="/images/m.webp" alt="" />
            <p>The Elder Scrolls Online: Gold Road</p>
          </NuxtLink>
          <NuxtLink href="/gameOfThrones" class="assassin_related_content_div">
            <img src="/images/d.webp" alt="" />
            <p>Game of Thrones: Legends</p>
          </NuxtLink>
        </div>
      </div>
    </div>
    <Contact />
    <Footer />
  </section>
</template>
