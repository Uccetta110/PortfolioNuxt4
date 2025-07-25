<template>
  <div class="container p-4 card w-auto projects">
    <div class="flex">
      <div class="content-center p-5 w-[35%]">
        <NuxtImg
          src="assets/images/Screenshot 2025-07-17 114337.png"
          alt="Io"
          class="images"
          @click="openFlappyDefenseLink"
        />
      </div>
      <div class="content-center p-5">
        <h1>FlappyDefense - JS</h1>
        <a
          href="https://github.com/Uccetta110/FlappyDefense"
          target="_blank"
          class="link"
        >
          <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
            alt="GitHub icon"
            style="width: 30px; height: auto; margin-right: 8px"
          />
          Uccetta110 - FlappyDefense
        </a>
      </div>
    </div>
    <div class="flex">
      <div class="content-center p-5 w-[35%]">
        <NuxtImg
          src="assets/images/word-image-3.png"
          alt="Io"
          class="images"
          @click="openFlappyMusicLink"
        />
      </div>
      <div class="content-center p-5">
        <h1>FlappyMusic - C#</h1>
        <a
          href="https://github.com/Uccetta110/FlappyMusic"
          target="_blank"
          class="link"
        >
          <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
            alt="GitHub icon"
            style="width: 30px; height: auto; margin-right: 8px"
          />
          Uccetta110 - FlappyMusic
        </a>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const openFlappyMusicLink = () => {
  window.open("https://github.com/Uccetta110/FlappyMusic", "_blank");
};

const openFlappyDefenseLink = () => {
  window.open("https://github.com/Uccetta110/FlappyDefense", "_blank");
};
</script>

<style scoped>
h1 {
  @apply font-bold text-6xl mb-5
}
</style>
