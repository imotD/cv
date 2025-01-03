<template>
  <div class="app">
    <Navbar />
    <Header />
    <Footer />
    <Sosmed />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Navbar from "./components/Navbar.vue";
import Sosmed from "./components/Sosmed.vue";
import Footer from "./components/Footer.vue"

export default {
  name: "App",
  components: {
    Header,
    Sosmed,
    Navbar,
    Footer
  },
};
</script>
