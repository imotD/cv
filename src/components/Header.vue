<template>
  <div
    class="header container mx-auto px-36 flex justify-center items-center grid grid-cols-1"
  >
    <div class="">
      <p>
        <span class="text-yellow-400 tracking-wide"> Halo, my name is</span>
      </p>
      <div class="py-5 text-5xl">
        <h1 class="">Tommy Alhamra.</h1>
        <h1 class="">I like to make something.</h1>
      </div>
      <p class="tracking-wide max-w-screen-sm">
        I'm a front-end developer specializing in building (and designing) great
        digital experiences. I’ve worked for a
        <span title="PT Weyland Indonesia Perkasa" class="underline">
          PT. WIP
        </span>
        as a web designer and front-end developer for 3 years, and right now I
        am looking forward to collaborate with you!
      </p>
      <br />
      <a href="mailto:tommy.alhamra@gmail.com">
        <button
          class="flex items-center p-2 border-yellow-400 border rounded tracking-wide"
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
  name: "Header"
};
</script>

<style lang="scss" scoped></style>
