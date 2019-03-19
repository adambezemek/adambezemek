<template>
  <footer
    class="w-full flex flex-wrap border-t border-grey-light p-4 text-xs tracking-wide leading-normal"
  >
    <p class="w-full text-center">
      This project is maintained by
      <a
        class="no-underline"
        href="https://github.com/adambezemek"
        target="_blank"
        >adambezemek</a
      >.<br />
      It was built with
      <a class="no-underline" href="https://nuxtjs.org/" target="_blank"
        >Nuxt.js</a
      >
      &amp;
      <a class="no-underline" href="https://tailwindcss.com" target="_blank"
        >Tailwind CSS</a
      >, and is hosted on
      <a class="no-underline" href="https://www.netlify.com" target="_blank"
        >Netlify.</a
      >
    </p>
  </footer>
</template>

<style lang="scss">
footer {
  @apply font-sans;
  @apply font-light;

  a {
    background: none;
  }
}
</style>
