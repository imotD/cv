<template>
  <nav
    class="
      flex flex-col
      md:flex-row
      justify-between
      md:items-center
      container
      mx-auto
      py-3
      px-5
    "
  >
    <div class="flex justify-between items-center">
      <div>
        <img width="40" src="../assets/logo.png" alt="" />
      </div>

      <button
        @click.stop="isOpen = !isOpen"
        class="text-yellow-300 block md:hidden"
      >
        <span
          class="iconify"
          :data-icon="`mdi:${isOpen ? 'close' : 'menu'}`"
          data-width="24"
        ></span>
      </button>
    </div>

    <div :class="`${isOpen ? 'block' : 'hidden'} md:block `">
      <div
        class="
          bg-gray-900
          md:bg-transparent
          text-sm
          flex flex-col
          md:flex-row
          pt-4
          mt-2
          md:mt-0 md:pt-0
          border-t border-gray-700
          md:border-t-0
        "
      >
        <a href="#" class="px-3 py-2 block md:inline-block">About</a>
        <a href="#" class="px-3 py-2 block md:inline-block">Experience</a>
        <a href="#" class="px-3 py-2 block md:inline-block">Work</a>
        <a href="#" class="px-3 py-2 block md:inline-block">Contact</a>
        <a
          href="../../pdf/CV_Tommy_Alhamra.pdf"
          download="CV_Tommy_Alhamra.pdf"
          target="_blank"
        >
          <button class="px-3 py-2 border border-yellow-300 rounded">
            Resume
          </button>
        </a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    openMenu() {
      this.isOpen = true;
    },
  },
};
</script>

<style lang="scss" scoped>
</style>