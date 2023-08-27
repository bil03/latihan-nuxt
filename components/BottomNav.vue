<template>
  <div class="h-full flex-col mt-12">
    <div class="flex bg-[#0A2647] flex-row justify-around text-white px-8 pt-8 w-full h-32">
      <div class="flex flex-col justyfy-center items-center">
        <h1 class="flex pb-2 text-lg ">Location</h1>
        <h1>Tanjungpinang</h1>
      </div>
      <div class="flex flex-col justyfy-center items-center">
        <h1 class="flex pb-2 text-lg ">Sosial media</h1>
        <ul class="flex flex-row justify-around w-64">
          <li>
            <a href="#">Instagram</a>
          </li>
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Tiktok</a></li>
        </ul>
      </div>
      <div class="flex flex-col justyfy-center items-center">
        <h1 class="flex pb-2 text-lg ">About Nongki Dimsum</h1>
        <h1>Tempat makan yang enak</h1>
      </div>
    </div>
    <div class="flex w-full bg-[#144272] h-10 justify-center items-center">
      <h1>©Copyright Nongki Dimsum</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderNav',
}
</script>