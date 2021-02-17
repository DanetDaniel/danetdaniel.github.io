<template>
  <div class="card-body p-12 rounded-2xl flex shadow-2xl ">
    <div class="left">
      <h1 class="text-8xl font-bold text-white">Hi, I’m Dani 👋</h1>
      <br>
      <h2 class="text-3xl font-semibold text-white mb-2">I help businesses create an online presence</h2>
      <h2 class="text-2xl font-semibold text-gray-300">by building websites and creating engaging content that will help them truly connect with their audience.</h2>
      <br>
      <h2 class="text-2xl font-semibold text-gray-300 mb-3">My skills include:</h2>
      <ul>
        <li class="underline text-white text-2xl font-semibold mb-3">Web Design</li>
        <li class="underline text-white text-2xl font-semibold mb-3">Web Development</li>
        <li class="underline text-white text-2xl font-semibold mb-3">Content Production</li>
      </ul>
      <hr class="border-yellow-500 border-2 mb-12">
      <div class="flex items-center">
        <n-link
          to="/contact"
          class="px-3 py-4 bg-yellow-500 text-white font-bold text-2xl rounded-md hover:bg-yellow-600 duration-100"
        >
          Let's work together!
        </n-link>
        <n-link
          to="/work"
          class="secondary-cta text-2xl font-semibold text-white ml-12 hover:text-gray-400 duration-100">
          See my work
          <i class="bi bi-arrow-right-short text-5xl"></i>
        </n-link>
      </div>
    </div>
    <div class="right">
      <HeroDD />
    </div>
  </div>
</template>

<script>
import HeroDD from './HeroDD';

export default {
  components: {
    HeroDD
  }
}
</script>

<style>
  .card-body {
    background: #101010;
  }

  .secondary-cta:hover i {
    margin-left: 12px;
    transition: all 100ms;
  }

  .right {
    width: 600px
  }
</style>