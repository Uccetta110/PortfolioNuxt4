<template>
  <NavComponent></NavComponent>
  <main>
    <slot></slot>
  </main>

  <footer class="bg-gray-800 text-white p-4 text-center mt-8">
    &copy; {{ new Date().getFullYear() }} Portfolio
  </footer>
</template>

