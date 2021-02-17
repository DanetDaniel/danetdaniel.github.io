<template>
  <header class="w-full">
    <div class="w-full flex justify-between items-center py-6">
      <!-- Branding -->
      <h1 class="font-bold text-3xl">Daniel Danet</h1>

      <!-- Navigation -->
      <nav>
        <n-link class="font-semibold text-xl text-gray-700 hover:text-gray-900 duration-100" to="/">About</n-link>
        <n-link class="ml-16 font-semibold text-xl text-gray-700 hover:text-gray-900 duration-100" to="/work">Work</n-link>
        <n-link class="ml-16 font-semibold text-xl text-gray-700 hover:text-gray-900 duration-100" to="/contact">Contact</n-link>
      </nav>
    </div>
    <hr>
  </header>
</template>

<script>
export default {
  name: "Navbar"
}
</script>

<style>
.nuxt-link-exact-active {
  @apply text-gray-900;
}
</style>