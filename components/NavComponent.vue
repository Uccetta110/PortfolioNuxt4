<template>
  <div>
    <header class="shadow-smb bg-[#eef4ed] h-auto">
      <nav class="flex items-center gap-4 container mx-auto p-4 justify-between">
        <h1 class="font-bold">Portfolio</h1>
        <ul class="flex gap-4 items-center">
          <li>
            <NuxtLink to="/" class="btn">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/school" class="btn">School</NuxtLink>
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
