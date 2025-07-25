<template>
  <NavComponent></NavComponent>
  <div class="container p-4 card w-auto my-20 mx-32">
    <main>
      <slot></slot>
    </main>
  </div>

  <footer class="bg-gray-800 text-white p-4 text-center mt-8">
    &copy; {{ new Date().getFullYear() }} Portfolio
  </footer>
</template>
