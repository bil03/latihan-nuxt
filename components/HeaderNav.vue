<template>
  <div
    class="flex bg-[#0A2647] w-full h-24 content-center justify-between items-center"
  >
    <h1 class="text-3xl text-white mx-8">Nongki Dimsum</h1>

    <div class="flex justify-between mx-8 w-72">
      <button
        type="button"
        class="text-white text-xl hover:text-[#2C74B3] active:text-[#2C74B3]"
      >
        <NuxtLink to="/"> Home </NuxtLink>
      </button>
      <button
        type="button"
        class="text-white text-xl hover:text-[#2C74B3] active:text-[#2C74B3]"
      >
        <NuxtLink to="/about"> About </NuxtLink>
      </button>
      <button
        type="button"
        class="text-white text-xl hover:text-[#2C74B3] active:text-[#2C74B3]"
      >
        <NuxtLink to="/contact"> Contact me </NuxtLink>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderNav',
}
</script>
