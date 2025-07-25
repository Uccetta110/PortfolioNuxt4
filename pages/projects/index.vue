<template>
  <div class="flex flex-col gap-y-5">
    <ProjectCard
      title="FlappyDefense - JS"
      imageSrc="assets/images/Screenshot 2025-07-17 114337.png"
      gitTitle="Uccetta110 - FlappyDefense"
      gitLink="https://github.com/Uccetta110/FlappyMusic"
      :clickFunction="openFlappyDefenseLink"
    ></ProjectCard>
    <ProjectCard
      title="FlappyMusic - C#"
      imageSrc="assets/images/word-image-3.png"
      gitTitle="Uccetta110 - FlappyMusic"
      gitLink="https://github.com/Uccetta110/FlappyMusic"
      :clickFunction="openFlappyMusicLink"
    ></ProjectCard>
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
