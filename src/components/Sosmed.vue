<template>
  <div class="sosmed">
    <div class="sosmed--left mb-5">
      <div v-for="i in icons" :key="i" class="mb-5">
        <a
          :href="i.link"
          target="_blank"
          class="transition hover:ease-in duration-300"
        >
          <button>
            <span
              class="iconify"
              :data-icon="`mdi:${i.icon}`"
              data-width="24"
            ></span>
          </button>
        </a>
      </div>
    </div>
    <div class="text-center text-xs py-4 tracking-wide font-robot">
      Made with Hope <br />
      © 2022 - by imotD
    </div>
    <!-- <div class="sosmed--right">
      <div>github</div>
      <div>instagram</div>
      <div>linkedin</div>
      <div>web</div>
    </div> -->
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
          icon: "notebook-outline",
          link: "https://tommyalhamra.medium.com/",
        },
        {
          icon: "web",
          link: "https://dottomuniverse.tech/",
        },
      ],
    };
  },
};
</script>
