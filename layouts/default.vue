<template>
  <div class="p-1 sm:p-3 md:p-10 lg:p-16 text-md lg:text-xl main">
    <!-- insert global navigation -->
    <Nav />
    <div class="p-6">
      <!-- insert page content -->
      <nuxt />
    </div>
    <!-- insert global footer -->
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Nav,
    Footer
  }
}
</script>
