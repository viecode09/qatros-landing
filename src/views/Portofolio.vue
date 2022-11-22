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

    <!-- Section 1 -->
    <div class="flex flex-col-reverse md:flex-row pt-[100px]">
      <!-- Conten Left -->
      <div
        class="flex flex-col w-[300px] mt-16 md:mt-0 md:w-[598px] md:h-[404px] m-auto text-center md:text-start">
        <h1 class="font-bold text-[28px] md:text-[30px] md:w-[475px]">
          SIKERJA (Sistem Informasi Kinerja)
        </h1>
        <p class="mt-2 text-[#727272]">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis odio
          et id quam mauris fusce. Donec nibh velit eget sem faucibus
          condimentum. Risus, urna, feugiat ut luctus lacus, nunc. Et mauris,
          proin faucibus lacus nisl volutpat. Sagittis, mauris, neque montes,
          sagittis, dis sed velit suspendisse vel. Vehicula erat vivamus nunc ac
          in ligula justo, risus sit. Diam mattis at non sed in urna dolor. Odio
          ut enim, ullamcorper quisque blandit suspendisse. volutpat. Sagittis,
          mauris, neque montes, sagittis, dis sed velit suspendisse vel.
          Vehicula erat vivamus nunc ac in ligula justo, risus sit. Diam mattis
          at non sed in urna dolor. Odio ut enim, ullamcorper quisque blandit
        </p>
        <div class="m-auto md:mx-0">
          <button
            class="border-none text-white flex bg-[#FFB800] w-[192px] h-[45px] rounded-lg mt-6 justify-center items-center pl-3">
            Mulai Sekarang
            <img
              src="../assets/images/i-mulai.png"
              alt="i-mulai"
              class="w-[22px] h-[22px] ml-3 m-auto" />
          </button>
        </div>
      </div>

      <!-- Conten Right -->
      <div class="flex flex-col m-auto md:w-[598px] md:h-[404px]">
        <img
          src="../assets/images/img-laptop.png"
          alt="img-laptop"
          class="w-[320px] md:w-[424px] md:h-[318px] m-auto" />
        <div class="m-auto mt-6 flex w-[300px] h-[24px]">
          <img
            src="../assets/images/i-price.png"
            alt="i-price"
            class="w-5 h-5 mr-2" />
          <p class="text-[#1EBD61] text-4">
            Estimasi Harga :
            <span class="font-semibold text-black pl-3">50jt - 200jt</span>
          </p>
        </div>
      </div>
    </div>

    <!-- Technology We Use -->
    <div class="flex flex-col pt-[100px]">
      <div class="m-auto">
        <h1 class="font-bold text-[28px] md:text-[36px]">Technology We Use</h1>
      </div>
      <div class="w-[310px] md:w-[535px] md:h-[86px] m-auto mt-10">
        <img src="../assets/images/i-framework.png" alt="i-framework" />
      </div>
    </div>

    <!-- Timeline -->
    <div class="flex flex-col pt-[150px]">
      <div class="m-auto">
        <h1 class="font-bold text-[28px] md:text-[36px] text-center">
          Timeline
        </h1>
        <div class="m-auto mt-10 w-[310px] md:w-full">
          <img src="../assets/images/img-timeline.png" alt="img-timeline" />
        </div>
      </div>
    </div>

    <!-- Gallery -->
    <div class="flex flex-col pt-[50px] mb-[150px]">
      <div class="m-auto">
        <h1 class="font-bold text-[28px] md:text-[36px] text-center">
          Gallery
        </h1>
      </div>
      <div class="flex flex-col md:flex-row md:justify-around pt-[72px]">
        <div class="flex flex-col m-auto md:m-0">
          <img
            src="../assets/images/gallery-1.png"
            alt="gallery-1"
            class="w-[300px] md:w-[400px] md:h-[400px]" />
          <img
            src="../assets/images/gallery-2.png"
            alt="gallery-2"
            class="w-[300px] md:w-[400px] md:h-[400px] mt-5" />
        </div>
        <div class="flex flex-col m-auto md:m-0 mt-5 md:mt-0">
          <img
            src="../assets/images/gallery-3.png"
            alt="gallery-3"
            class="w-[300px] md:w-[400px] md:h-[400px]" />

          <img
            src="../assets/images/gallery-4.png"
            alt="gallery-4"
            class="w-[300px] md:w-[400px] md:h-[400px] mt-5" />
        </div>
        <div class="flex flex-col m-auto md:m-0 mt-5 md:mt-0">
          <img
            src="../assets/images/gallery-5.png"
            alt="gallery-5"
            class="w-[300px] md:w-[400px] md:h-[400px]" />

          <img
            src="../assets/images/gallery-6.png"
            alt="gallery-6"
            class="w-[300px] md:w-[400px] md:h-[400px] mt-5" />
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>
