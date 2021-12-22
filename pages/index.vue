<template>
  <div>
    <b-container fluid="lg">
      <Nav />
      <GreenNav />
      <Hero />
      <Footer />
    </b-container>
  </div>
</template>

<script>
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Footer,
  },
};
</script>
