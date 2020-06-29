<template>
  <div class="container mx-auto px-40">
    <div>
      <!-- <h1 class="title">Hello</h1>
      <h2 class="subtitle">I'm Mehdi Boujenan</h2>
      <h2 class="subtitle">And it's all gonna be alright :)</h2>-->
    </div>
    <div class="md:flex">
      <Logo />

      <div class="mt-4 md:mt-0 md:ml-6">
        <h1 class="title">Hello</h1>
        <h2 class="subtitle">I'm Mehdi Boujenan</h2>

        <h2 class="subtitle">And it's all gonna be alright :)</h2>
      </div>
      <div class="links">
        <!-- <a href="https://nuxtjs.org/" target="_blank" class="button--green"
          >Documentation</a
        >-->
        <!-- <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
          >GitHub YOP HOLALALA</a
        >-->
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo,
  },
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS */
/* .container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
} */

.container {
  margin: 0;
  /* margin: 0 auto; */
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 6.85rem;
  color: #35495e;
}

.subtitle {
  font-weight: 300;
  font-size: 1.5rem;
  color: #526488;
  padding-bottom: 10px;
}

/* Large (lg) */
@media (min-width: 1280px) {
  .title {
    letter-spacing: 1px;
  }
  .subtitle {
    font-size: 42px;
    word-spacing: 5px;
    padding-bottom: 15px;
  }
}

.links {
  padding-top: 15px;
}
</style>
