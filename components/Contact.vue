<script setup lang="ts">
import Button from "./Button.vue";
</script>

<template>
  <section class="contact">
    <p class="contact_left">
      <span class="contact_span">[</span>Contact US<span class="contact_span"
        >]</span
      >
    </p>
    <div class="contact_right">
      <h3>
        Ready to expand your world? <br />
        Let’s make something unforgettable.
      </h3>
      <div class="form">
        <div>
          <input type="text" id="name" name="name" placeholder="Name" /><br />
          <input
            type="text"
            id="name"
            name="name"
            placeholder="Email address"
          /><br />
          <input
            type="text"
            id="name"
            name="name"
            placeholder="Company"
          /><br />
          <input
            type="text"
            id="name"
            name="name"
            placeholder="Project Type"
          /><br />
        </div>
        <Button class="c_button" />
      </div>
    </div>
  </section>
</template>
