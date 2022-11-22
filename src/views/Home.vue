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
    <img
      src="../assets/images/bg-blur.png"
      alt="bg-blur"
      class="invisible md:visible md:bg-cover absolute w-[476px]" />

    <!--   Buat Rencana Bisnis Anda Dengan Pakar Teknologi Kami -->
    <div id="home" class="flex w-full pt-[150px] flex-col-reverse md:flex-row">
      <div
        class="m-auto text-center md:text-start flex justify-center flex-col">
        <h1 class="font-bold text-[28px] md:text-[48px] md:w-[531px] z-10">
          Buat Rencana Bisnis Anda Dengan Pakar Teknologi Kami
        </h1>
        <p class="text-[#6C6C6C] mt-[24px] z-30">
          Rancang aplikasi web dan mobile kamu sesuai dengan keinginan!
        </p>
        <div class="m-auto md:mx-0 z-10">
          <button
            class="border-none text-white flex bg-[#FFB800] w-[192px] h-[45px] rounded-lg mt-6 justify-center items-center pl-3 z-10">
            Mulai Sekarang
            <img
              src="../assets/images/i-mulai.png"
              alt="i-mulai"
              class="w-[22px] h-[22px] ml-3 m-auto" />
          </button>
        </div>
      </div>
      <!-- Image -->
      <div class="m-auto z-10">
        <img
          src="../assets/images/hero-illustrasi-1.png"
          alt="img-ilustrasi1"
          class="w-[300px] mt-[-50px] md:w-[448px]" />
      </div>
    </div>

    <img
      src="../assets/images/Kotak.png"
      alt="kotak"
      class="invisible md:visible md:bg-cover absolute right-0 my-40 z-10 w-[150px]" />

    <img
      src="../assets/images/Ellipse-98.png"
      alt="bg-blur"
      class="invisible md:visible md:bg-cover absolute right-0 w-[513px] -my-48" />

    <!-- Kami Adalah Partner Yang Tepat -->
    <div class="flex flex-col md:flex pt-[100px]">
      <div class="flex flex-col text-center m-auto">
        <img
          src="../assets/images/bg-bullet.png"
          alt="bg-blur"
          class="bg-cover w-[30px] h-[30px] md:w-[36px] md:h-[36px] mx-3 md:mx-[-11px]" />
        <h3
          class="font-bold text-[28px] md:text-[36px] mt-[-27px] md:mt-[-35px] z-10">
          Kami Adalah Partner Yang Tepat
        </h3>
        <p class="mt-[15px] md:w-[500px] text-[#6C6C6C]">
          kami dapat membantumu tumbuh dan berkembang di beberapa aspek untuk
        </p>
      </div>
    </div>
    <div class="flex flex-col m-auto w-[300px] md:w-full md:flex-row mt-8">
      <div class="m-auto pt-8">
        <img
          src="../assets/images/Ellipse-black.png"
          alt="bg-1-yellow"
          class="bg-cover" />
        <img
          src="../assets/images/Ellipse-yellow.png"
          alt="bg-2-black"
          class="bg-cover mt-[-230px] md:mt-[-375px]" />
        <img
          src="../assets/images/hero-ilutrasi-2.png"
          alt="img-ilustrasi2"
          class="md:w-[456px] md:h-[445px] mt-[-200px] md:mt-[-400px]" />
      </div>
      <div class="m-auto pt-10 md:pt-0 md:w-[526px] z-10">
        <p class="flex items-center">
          <img
            src="../assets/images/i-ceklis.png"
            alt="i-check"
            class="w-[28px] h-[28px] mr-8" />
          Qatros menawarkan solusi percepatan bisnis dengan teknologi yang
          optimal.
        </p>
        <p class="pt-8 flex items-center">
          <img
            src="../assets/images/i-ceklis.png"
            alt="i-check"
            class="w-[28px] h-[28px] mr-8" />
          Roro jonggrang development untuk anda yang ingin segera rilis dan go
          public.
        </p>
        <p class="pt-8 flex items-center">
          <img
            src="../assets/images/i-ceklis.png"
            alt="i-check"
            class="w-[28px] h-[28px] mr-8" />
          Harga yang kompetitif dan bisa disesuaikan dengan timeline anda.
        </p>
        <p class="pt-8 flex items-center">
          <img
            src="../assets/images/i-ceklis.png"
            alt="i-check"
            class="w-[28px] h-[28px] mr-8" />
          Qatros memberikan pendampingan dari mulai penyusunan timeline hingga
          after rilis.
        </p>
      </div>
    </div>

    <img
      src="../assets/images/bg-Kotak.png"
      alt="kotak"
      class="invisible md:visible md:bg-cover absolute my-56 mx-8" />
    <!-- Siapa Qatros -->
    <div class="flex flex-col md:flex pt-[150px]">
      <div class="m-auto">
        <img
          src="../assets/images/bg-bullet.png"
          alt="bg-blur"
          class="bg-cover w-[30px] h-[30px] md:w-[36px] md:h-[36px] mx-[-14px] md:mx-[-16px]" />
        <h3
          class="font-bold text-[28px] md:text-[36px] mt-[-27px] md:mt-[-35px]">
          Siapa Qatros?
        </h3>
      </div>
      <div class="flex flex-col-reverse md:flex-row mt-5">
        <div
          class="pt-[40px] w-[300px] text-center md:w-[598px] m-auto md:text-start">
          <p class="text-justify text-[13px] md:text-left md:text-[16px]">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis odio
            et id quam mauris fusce. Donec nibh velit eget sem faucibus
            condimentum. Risus, urna, feugiat ut luctus lacus, nunc. Et mauris,
            proin faucibus lacus nisl volutpat. Sagittis, mauris, neque montes,
            sagittis, dis sed velit suspendisse vel. Vehicula erat vivamus nunc
            ac in ligula justo, risus sit. Diam mattis at non sed in urna dolor.
            Odio ut enim, ullamcorper quisque blandit suspendisse. volutpat.
            Sagittis, mauris, neque montes, sagittis, dis sed velit suspendisse
            vel. Vehicula erat vivamus nunc ac in ligula justo, risus sit. Diam
            mattis at non sed in urna dolor. Odio ut enim, ullamcorper quisque
            blandit
          </p>
          <a href="#" class="flex text-[#FFB800] pt-4"
            >Lihat Selengkapnya
            <img
              src="../assets/images/i-panah.png"
              alt="i-panah"
              class="pl-2 pt-1 w-[26px] h-[20px]"
          /></a>
        </div>
        <div class="m-auto md:mt-[-60px] z-10">
          <img
            src="../assets/images/hero-ilustrasi-3.png"
            alt="img-ilutrasi3"
            class="w-[320px]" />
        </div>
      </div>
    </div>
    <img
      src="../assets/images/Ellipse-98.png"
      alt="bg-blur"
      class="invisible md:visible md:bg-cover absolute right-0 -my-40 w-[272px] h-[265px]" />

    <img
      src="../assets/images/Kotak.png"
      alt="kotak"
      class="invisible md:visible md:bg-cover absolute right-36 my-40 z-10 w-[150px]" />

    <!-- Layanan Kami -->
    <div id="layanankami" class="flex flex-col pt-[150px]">
      <div class="m-auto">
        <img
          src="../assets/images/bg-bullet.png"
          alt="bg-blur"
          class="bg-cover w-[30px] h-[30px] md:w-[36px] md:h-[36px] mx-[-14px] md:mx-[-16px]" />
        <h3
          class="font-bold text-[28px] md:text-[36px] mt-[-27px] md:mt-[-35px]">
          Layanan Kami
        </h3>
      </div>

      <div
        class="flex mx-10 md:mx-36 mt-4 md:mt-11 flex-col md:justify-around md:flex-row">
        <!-- Container Left -->

        <div class="justify-start">
          <router-link to="/layanan-kami">
            <div
              class="w-[300px] md:w-[331px] h-[96px] border-none rounded-lg p-5 hover:bg-[#FFB800] hover:text-white">
              <h5 class="font-bold">Ngegawe</h5>
              <p class="text-xs">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis
                felis.
              </p>
            </div>
          </router-link>
          <router-link to="/layanan-kami">
            <div
              class="w-[300px] md:w-[331px] h-[96px] border-none rounded-lg p-5 hover:bg-[#FFB800] hover:text-white">
              <h5 class="font-bold">Ngegawe</h5>
              <p class="text-xs">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis
                felis.
              </p>
            </div>
          </router-link>
          <router-link to="/layanan-kami">
            <div
              class="w-[300px] md:w-[331px] h-[96px] border-none rounded-lg p-5 hover:bg-[#FFB800] hover:text-white">
              <h5 class="font-bold">Ngegawe</h5>
              <p class="text-xs">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis
                felis.
              </p>
            </div>
          </router-link>
        </div>

        <!-- Container Center & right -->
        <div class="m-auto flex flex-col md:flex-row mt-4 md:mt-0">
          <div
            class="border-2 border-[#FFF1BF] hover:bg-[#FFF9E0] w-[300px] md:w-[351px] h-[210px] flex justify-center items-center md:mr-8 md:ml-4">
            <div
              class="w-[280px] md:w-[325px] h-[118px] text-center flex flex-col justify-center items-center">
              <img
                src="../assets/images/i-webdev.png"
                alt="i-webdev"
                class="w-[50px] h-[51px] mt-[46px]" />
              <h5 class="mt-[27px] font-semibold">Development Service</h5>
              <p class="text-xs text-[#616161]">
                Our support team will get assistance from AI-Powered
              </p>
            </div>
          </div>
          <div
            class="border-2 border-[#FFF1BF] hover:bg-[#FFF9E0] w-[300px] mt-3 md:mt-0 md:w-[351px] h-[210px] flex justify-center items-center">
            <div
              class="w-[280px] md:w-[325px] h-[118px] text-center flex flex-col justify-center items-center">
              <img
                src="../assets/images/i-webdev.png"
                alt="i-webdev"
                class="w-[50px] h-[51px] mt-[46px]" />
              <h5 class="mt-[27px] font-semibold">Development Service</h5>
              <p class="text-xs text-[#616161]">
                Our support team will get assistance from AI-Powered
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <img
      src="../assets/images/Ellipse-99.png"
      alt="bg-blur"
      class="invisible md:visible md:bg-cover absolute my-16 h-[700px]" />
    <!-- Portofolio -->
    <div class="flex flex-col pt-[120px]" id="portofolio">
      <div class="m-auto">
        <img
          src="../assets/images/bg-bullet.png"
          alt="bg-blur"
          class="bg-cover w-[30px] h-[30px] md:w-[36px] md:h-[36px] mx-[-14px] md:mx-[-16px]" />
        <h3
          class="font-bold text-[28px] md:text-[36px] mt-[-27px] md:mt-[-35px]">
          Portofolio
        </h3>
      </div>
      <div
        class="flex flex-col jusitfy-center items-center md:flex-row m-auto mt-4 md:mt-20 z-10">
        <!-- Container Left -->
        <div class="w-[300px] md:w-[400px] h-[366px] md:mr-4">
          <div class="w-[300px] md:w-[400px] h-[410px]">
            <img src="../assets/images/img-laptop.png" alt="img-laptop" />
            <div class="text-center mt-5">
              <h5 class="font-semibold">KEMENDAGRI</h5>
              <p class="text-xs text-[#616161]">Sistem Informasi Kerja</p>
              <button
                class="border rounded-lg w-[73px] h-[32px] mt-2 hover:bg-slate-400">
                Detail
              </button>
            </div>
          </div>
        </div>
        <!-- Container Center -->
        <div class="w-[300px] md:w-[400px] h-[366px] md:mr-4">
          <div class="w-[300px] md:w-[400px] h-[410px]">
            <img src="../assets/images/img-ptot.png" alt="img-ptot" />
            <div class="text-center mt-5">
              <h5 class="font-semibold">PT Orang Tua</h5>
              <p class="text-xs text-[#616161]">
                Mor’e Marketplace by PT Orang Tua
              </p>
              <button
                class="border rounded-lg w-[73px] h-[32px] mt-2 hover:bg-slate-400">
                Detail
              </button>
            </div>
          </div>
        </div>
        <!-- Container Right -->
        <div class="w-[300px] md:w-[400px] h-[366px]">
          <div class="w-[300px] md:w-[400px] h-[410px]">
            <img src="../assets/images/img-finance.png" alt="img-finance" />
            <div class="text-center mt-5">
              <h5 class="font-semibold">PT Bank Mega</h5>
              <p class="text-xs text-[#616161]">Mega Finance</p>

              <button
                class="border rounded-lg w-[73px] h-[32px] mt-2 hover:bg-slate-400">
                Detail
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-col m-auto mt-[20px] md:mt-[80px]">
        <router-link to="/portofolio">
          <button class="text-white bg-[#1E1135] rounded-lg w-[137px] h-[40px]">
            Lebih Banyak
          </button>
        </router-link>
      </div>
    </div>

    <!-- Trust -->
    <div class="flex flex-col md:flex-row pt-[150px]">
      <div class="m-auto text-center md:text-start">
        <p
          class="text-lg text-center md:text-start text-[#FFB800] font-semibold">
          Trust
        </p>
        <h1 class="font-bold mt-[15px] md:w-[475px] text-[28px] md:text-[32px]">
          Dipercaya oleh beberapa Perusahaan Besar
        </h1>
        <p
          class="text-xs text-center md:text-start text-[#616161] md:w-[598px] mt-5">
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
      </div>
      <div class="md:flex m-auto mt-[30px]">
        <div class="flex-col md:mr-6">
          <img
            src="../assets/images/i-kemendagri.png"
            alt="i-kemendagri"
            class="w-[70px] h-[93px] m-auto" />
          <img
            src="../assets/images/i-privy.png"
            alt="i-privy"
            class="w-[166px] h-[40px] mt-5 md:mt-[63px] m-auto" />
        </div>
        <div class="flex-col md:mr-6 mt-6">
          <img
            src="../assets/images/i-ot.png"
            alt="i-ptot"
            class="w-[110px] h-[59px] m-auto" />
          <img
            src="../assets/images/i-mandiri.png"
            alt="i-mandiri"
            class="w-[128px] h-[40px] mt-6 md:mt-[70px] m-auto" />
        </div>
        <div class="flex-col mt-5">
          <img
            src="../assets/images/i-kindo.png"
            alt="i-kindo"
            class="w-[124px] h-[78px] m-auto" />
          <img
            src="../assets/images/i-cimb.png"
            alt="i-cimb"
            class="w-[173px] h-[40px] mt-5 md:mt-[60px] m-auto" />
        </div>
      </div>
    </div>

    <!-- Start Your Project With Qatros -->
    <div
      class="flex flex-col-reverse w-[300px] md:flex-row m-auto justify-center items-center border-2 rounded-lg md:h-[390px] md:w-[1160px] mt-[150px]">
      <img
        src="../assets/images/hero-ilustrasi4.png"
        alt="hero-4"
        class="h-[344px] md:w-[310px] md:h-[384px]" />
      <div class="m-auto md:mx-0 pt-4 z-10">
        <h1
          class="font-bold w-[300px] md:w-[450px] text-center md:text-start text-[28px] md:text-[48px]">
          Start your project with <span class="text-[#FFB800]">Qatros!</span>
        </h1>
        <p
          class="text-xs text-[#616161] text-center md:text-start mt-6 md:w-[430px]">
          With our IT experts, we bring innovation from drop to level up your
          business with a world class technology standard.
        </p>

        <button
          class="m-auto md:mx-0 mb-4 border-none text-white flex bg-[#FFB800] w-[192px] h-[45px] rounded-lg mt-6 justify-center items-center pl-3">
          Mulai Sekarang
          <img
            src="../assets/images/i-mulai.png"
            alt="i-mulai"
            class="w-[22px] h-[22px] ml-3 m-auto" />
        </button>
      </div>
    </div>

    <!-- Blog -->
    <div id="blog" class="flex flex-col pt-[120px] mb-[150px]">
      <div class="m-auto">
        <h3 class="font-bold text-[28px] md:text-[36px]">Blog</h3>
      </div>
      <div
        class="flex flex-col m-auto mt-4 md:flex-row md:justify-around md:m-0 md:mt-[72px]">
        <!-- Continer Kiri 1 -->
        <div class="rounded-lg w-[300px] md:h-[346px] border-2">
          <img
            src="../assets/images/img-konten1.png"
            alt="konten1"
            class="h-[160] w-full rounded-lg" />
          <h4 class="p-3 w-[250px] h-[72px] text-left mt-4 font-semibold">
            Prinsip-prinsip Kanban yang ada di Hari Kesaktian Pancasila
          </h4>
          <div class="flex mt-[25px] w-full p-3">
            <img
              src="../assets/images/i-Mask.png"
              alt="mask"
              class="w-[40px] h-[40px]" />
            <div class="flex flex-col pl-3">
              <p class="text-xs font-semibold">Admin Qatros 1</p>
              <p class="text-xs text-[#616161]">Dec 10, 2020 • Teknologi</p>
            </div>
            <img
              src="../assets/images/i-share.png"
              alt="i-sahre"
              class="w-[36px] h-[36px] ml-10" />
          </div>
        </div>
        <!-- Container Kiri 2 -->
        <div class="rounded-lg w-[300px] h-[346px] border-2 mt-4 md:mt-0">
          <img
            src="../assets/images/img-konten2.png"
            alt="konten1"
            class="h-[160] w-full rounded-lg" />
          <h4 class="p-3 w-[250px] h-[72px] text-left mt-4 font-semibold">
            Yang Harus Kamu Tau dari Layanan Streaming Podcast
          </h4>
          <div class="flex mt-[25px] w-full p-3">
            <img
              src="../assets/images/i-Mask.png"
              alt="mask"
              class="w-[40px] h-[40px]" />
            <div class="flex flex-col pl-3">
              <p class="text-xs font-semibold">Admin Qatros 1</p>
              <p class="text-xs text-[#616161]">Dec 10, 2020 • Teknologi</p>
            </div>
            <img
              src="../assets/images/i-share.png"
              alt="i-sahre"
              class="w-[36px] h-[36px] ml-10" />
          </div>
        </div>
        <!-- Container Kanan 1 -->
        <div class="rounded-lg w-[300px] h-[346px] border-2 mt-4 md:mt-0">
          <img
            src="../assets/images/img-konten3.png"
            alt="konten1"
            class="h-[160] w-full rounded-lg" />
          <h4 class="p-3 w-[250px] h-[72px] text-left mt-4 font-semibold">
            Mengenal Scrum: Treatment Untuk Produk dan Project Yang Kompleks
          </h4>
          <div class="flex mt-[25px] w-full p-3">
            <img
              src="../assets/images/i-Mask.png"
              alt="mask"
              class="w-[40px] h-[40px]" />
            <div class="flex flex-col pl-3">
              <p class="text-xs font-semibold">Admin Qatros 1</p>
              <p class="text-xs text-[#616161]">Dec 10, 2020 • Teknologi</p>
            </div>
            <img
              src="../assets/images/i-share.png"
              alt="i-sahre"
              class="w-[36px] h-[36px] ml-10" />
          </div>
        </div>
        <!-- Container Kanan 2 -->
        <div class="rounded-lg w-[300px] h-[346px] border-2 mt-4 md:mt-0">
          <img
            src="../assets/images/img-konten4.png"
            alt="konten1"
            class="h-[160] w-full rounded-lg" />
          <h4 class="p-3 w-[250px] h-[72px] text-left mt-4 font-semibold">
            Mengenal Internet of Things (IoT)
          </h4>
          <div class="flex mt-[25px] w-full p-3">
            <img
              src="../assets/images/i-Mask.png"
              alt="mask"
              class="w-[40px] h-[40px]" />
            <div class="flex flex-col pl-3">
              <p class="text-xs font-semibold">Admin Qatros 1</p>
              <p class="text-xs text-[#616161]">Dec 10, 2020 • Teknologi</p>
            </div>
            <img
              src="../assets/images/i-share.png"
              alt="i-sahre"
              class="w-[36px] h-[36px] ml-10" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <Footer />
</template>
