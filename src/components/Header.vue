<template>
  <div
    class="header container mx-auto md:px-36 px-6 flex justify-center items-center grid grid-cols-1"
  >
    <div class="">
      <p>
        <span class="text-yellow-300 tracking-wide">Halo, my name is</span>
      </p>
      <div class="py-5 text-5xl font-bold">
        <h1 class="text-light">Tommy Alhamra.</h1>
        <h1>{{ slogan }}</h1>
      </div>
      <p class="tracking-wide max-w-screen-sm">
        As a Frontend Developer, I have been a professional in the industry for
        3+ years in startup companies. Throughout my journey I have developed
        skills in HTML5, CSS3/SCSS, Vue.js, Vuex, React,Javascript. It is my
        passion to create web projects. I hope I can help you with what you
        need!
      </p>
      <br />
      <a :href="email" class="transition hover:ease-in duration-300">
        <button
          class="hover:bg-yellow-700 hover:text-white flex items-center p-2 border-yellow-300 border rounded tracking-wide font-robot"
        >
          <span
            class="iconify mr-1"
            data-icon="mdi:email-outline"
            data-width="24"
          ></span>
          Email Me
        </button>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      slogan: 'I like to make something.',
      email: 'mailto:tommy.alhamra@gmail.com  ',
    };
  },
};
</script>

<style lang="scss" scoped></style>
