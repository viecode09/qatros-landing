<script>
import Navbar from '../components/Navbar.vue';
import Footer from '../components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<template>
  <div class="w-full">
    <Navbar />

    <!-- button Back -->
    <div class="flex pt-[150px]">
      <router-link to="/">
        <button class="w-[98px] h-[24px] mx-8 md:mx-[50px] flex">
          <img
            src="../assets/images/i-back.png"
            alt="i-back"
            class="h-[12px] w-[6px] mr-2 mt-[6px]" />
          <h3 class="font-semibold text-[16px] w-[460px] h-[90px]">Kembali</h3>
        </button>
      </router-link>
    </div>

    <!-- Section -->
    <div
      class="flex flex-col-reverse pt-[70px] md:pt-[100px] mb-[150px] md:flex-row">
      <!-- Conten Left -->
      <div
        class="flex flex-col w-[300px] md:w-[598px] md:h-[404px] m-auto text-center md:text-start mt-5 md:mt-0">
        <img
          src="../assets/images/bg-Nggawe.png"
          alt="bg-nggawe"
          class="ml-[-62px] md:ml-[-75px]" />
        <h1
          class="font-bold text-[28px] md:text-[30px] md:w-[691px] w-[300px] mt-[-60px] md:mt-[-120px]">
          Pembuatan Aplikasi <span class="text-[#FFB800]">Web / Mobile</span>
        </h1>
        <p class="mt-2 text-[#727272]">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tortor lorem
          velit dapibus tellus vulputate sit sit sed vulputate. Ante volutpat
          suspendisse faucibus pharetra, diam egestas nibh nibh. Lacus, in duis
          amet elit, odio elit sodales aenean pellentesque. Neque id urna ac
          cras sed eu, ullamcorper sed scelerisque. Sagittis felis montes,
          scelerisque et in ac ultricies blandit. Nam id aliquam sagittis,
          facilisis auctor pellentesque urna, nibh. Quis vulputate.
        </p>
        <button
          class="w-[300px] h-[40px] rounded bg-[#FFB800] font-semibold mt-[30px] text-4 text-center">
          Buat Aplikasi Impianmu Sekarang
        </button>
      </div>

      <!-- Conten Right -->
      <div class="flex flex-col md:w-[598px] md:h-[404px] md:mt-5 mt-0">
        <img
          src="../assets/images/img-conten1.png"
          alt="img-conten1"
          class="w-[320px] md:w-[450px] md:h-[300px] m-auto mt-[5px]" />
      </div>
    </div>

    <img
      src="../assets/images/bg-Kotak.png"
      alt="bg-kotak"
      class="ml-3 w-[50px] md:w-[90px] md:h-[200px]" />
    <Footer class="mt-[-110px] md:mt-[-210px]" />
  </div>
</template>
