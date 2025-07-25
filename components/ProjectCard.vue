<template>
  <div class="flex flex-col gap-5 sm:flex-col lg:flex-row">
    <div class="w-full lg:w-[35%] flex items-center justify-center">
      <NuxtImg
        :src="imageSrc"
        alt="Io"
        class="images"
        @click="clickFunction"
      />
    </div>  
    <div class="content-center">
      <h1 class="font-bold lg:text-6xl sm:text-4xl mb-5 text-center">{{title}}</h1>
      <a
        href="https://github.com/Uccetta110/FlappyDefense"
        target="_blank"
        class="link text-center"
      >
        <img
          src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
          alt="GitHub icon"
          style="width: 30px; height: auto; margin-right: 8px"
        />
        {{gitTitle}}
      </a>
    </div>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  imageSrc: { type: String, required: true },
  clickFunction: { type: Function, required: true },
  title: { type: String, required: true },
  gitTitle: { type: String, required: true },
  gitLink: { type: String, required: true }
});
</script>