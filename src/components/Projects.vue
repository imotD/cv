<template>
  <div class="container mx-auto px-6">
    <h2 class="text-4xl font-bold">Highlight Project 🚀</h2>
    <p class="mb-7">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus,
      eveniet!
    </p>
    <div class="grid grid-cols-3 gap-4">
      <div v-for="i in 3" :key="i" class="h-80 bg-pink-800 p-6">
        <h4 class="text-2xl mb-2">Judul</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere,
          nostrum!
        </p>
      </div>
    </div>
    <div class="flex justify-center my-4">
      <a :href="email" class="transition hover:ease-in duration-300">
        <button
          class="hover:bg-yellow-700 hover:text-white flex items-center p-2 border-blue-800 border rounded tracking-wide font-robot"
        >
          <span
            class="iconify mr-1"
            data-icon="mdi:github"
            data-width="24"
          ></span>
          See More
        </button>
      </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
