<template>
  <div class="sosmed">
    <div class="sosmed--left mb-5 hidden md:block justify-center">
      <div v-for="(icon, i) in icons" :key="i" class="mb-5">
        <a
          :href="icon.link"
          target="_blank"
          class="transition hover:ease-in duration-300"
        >
          <button class="hover:text-yellow-300">
            <span
              class="iconify"
              :data-icon="`mdi:${icon.icon}`"
              data-width="24"
            ></span>
          </button>
        </a>
      </div>
    </div>

    <div>
      <div class="flex justify-center md:hidden">
        <a
          v-for="(icon, i) in icons"
          :key="i"
          :href="icon.link"
          target="_blank"
          class="transition hover:ease-in duration-300 p-2 flex items-center"
        >
          <button class="hover:text-yellow-300">
            <span
              class="iconify"
              :data-icon="`mdi:${icon.icon}`"
              data-width="24"
            ></span>
          </button>
        </a>
      </div>

      <div class="text-center text-xs py-4 tracking-wide font-robot">
        Made with Hope <br />
        © 2022 - by imotD
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Sosmed",
  data() {
    return {
      icons: [
        {
          icon: "github",
          link: "https://github.com/imotD",
        },
        {
          icon: "linkedin",
          link: "https://www.linkedin.com/in/tommy-alhamra/",
        },
        {
          icon: "book-open-variant",
          link: "https://tommyalhamra.medium.com/",
        },
        {
          icon: "web",
          link: "https://dottomuniverse.netlify.app/",
        },
      ],
    };
  },

};
</script>
