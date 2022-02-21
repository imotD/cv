<template>
  <nav class="flex container mx-auto justify-between items-center py-3">
    <div>
      <img width="40" src="../assets/logo.png" alt="" />
    </div>
    <div class="text-sm">
      <span class="px-3 py-2">About</span>
      <span class="px-3 py-2">Experience</span>
      <span class="px-3 py-2">Work</span>
      <span class="px-3 py-2">Contact</span>
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
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
</style>