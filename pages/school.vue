<template>
  <div class=" flex-col gap-5">
    <div class="content-center p-5 flex w-[100%] items-center justify-end">
      <h1 class="p5 text-right text-4xl">Paleocapa Esperia</h1>
      <NuxtImg
        src="/assets/images/il-museo-dellindustria-trova-casataglio-del-nastro-a-giugno-allesperia_01a5219c-c206-11e5-9dd2-d7a5b91d6d64_700_455_big_gallery_linked_i.jpg"
        alt="Io"
        class="images"
        @click="openPalEspLink"
      />
    </div>
    <div class="content-center p-5 flex items-center">
      <NuxtImg
        src="/assets/images/images.jfif"
        alt="Io"
        class="images"
        @click="openIndInfLink"
      />
      <h1 class="text-4xl">Indirizzo Informatico</h1>
    </div>
    <div class="content-center p-5 flex items-center justify-end">
      <h1 class="p5 text-right text-4xl">Dove si trova</h1>
      <NuxtImg
        src="/assets/images/Screenshot 2025-07-17 121257.png"
        alt="Io"
        class="images "
        @click="openPosLink"
      />
    </div>
  </div>
</template>

<script setup lang="ts">
const openIndInfLink = () => {
  window.open("https://www.itispaleocapa.edu.it/", "_blank");
};

const openPalEspLink = () => {
  window.open(
    "https://www.itispaleocapa.edu.it/istituto/informatica/",
    "_blank"
  );
};

const openPosLink = () => {
  window.open(
    "https://www.itispaleocapa.edu.it/istituto/dove-siamo/",
    "_blank"
  );
};
</script>

<style scoped>
h1 {
  @apply font-bold text-5xl mb-5;
}
</style>
