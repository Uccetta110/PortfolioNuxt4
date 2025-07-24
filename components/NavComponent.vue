<template>
  <div>
    <header class="shadow-smb bg-[#eef4ed]">
      <nav class="container mx-auto p-4 flex justify-between content-center">
        <h1 class="font-bold">Portfolio</h1>
        <ul class="flex gap-4 content-center justify-between">
          <li>
            <NuxtLink to="/" class="btn">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/school" class="btn">school</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/projects" class="btn">Projects</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<style scoped>
  .router-link-exact-active {
    color: #12b488;
  }
</style>
