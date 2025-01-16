<template>
  <div class="app">
    <Navbar />
    <Header />
    <Projects />
    <Skill />
    <Footer />
    <Sosmed />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Projects from './components/Projects.vue';
import Sosmed from './components/Sosmed.vue';
import Footer from './components/Footer.vue';
import Skill from './components/Skill.vue';

export default {
  name: 'App',
  components: {
    Header,
    Sosmed,
    Navbar,
    Footer,
    Projects,
    Skill,
  },
};
</script>
