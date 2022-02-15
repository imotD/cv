<template>
  <div class="app">
    <Header />
    <Sosmed />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Sosmed from "./components/Sosmed.vue";

export default {
  name: "App",
  components: {
    Header,
    Sosmed,
  },
};
</script>
