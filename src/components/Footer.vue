<template>
  <div class="w-full">
    <!-- Footer -->
    <hr class="w-[300px] md:w-[1150px] m-auto shadow" />
    <div class="flex flex-col md:flex-row md:justify-between">
      <!-- Container Left -->
      <div class="flex flex-col w-[340px] m-auto p-2 md:p-0">
        <div class="mt-4">
          <img
            src="../assets/images/logo-qatros.png"
            alt="logo-qatros"
            class="w-[195px] md:mt-[35px]" />
        </div>
        <div class="w-[300px] md:w-[365px] mt-5 md:mt-0">
          <h5 class="font-semibold text-[20px] mt-[25px]">
            PT. Qatros Teknologi Nusantara
          </h5>
          <p class="text-[16px] mt-2">
            Setan, Setan, Jl. Sarirejo No.2, Setan, Maguwoharjo, Depok
            Sub-District, Sleman Regency, Special Region of Yogyakarta 55281
          </p>
          <p class="text-[20px] mt-[20px]">Follow Us</p>
          <img
            src="../assets/images/Socmed.png"
            alt="sosmed"
            class="w-[144px] h-[24px] mt-[20px]" />
        </div>
      </div>

      <!-- Container Right -->
      <div
        class="flex flex-col p-14 md:flex-row md:justify-around md:m-auto md:p-0">
        <div
          class="flex flex-col justify-start items-start mt-2 md:mt-[65px] md:mr-[50px]">
          <h6 class="font-bold text-lg">Product</h6>
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >Getdebug</a
          >
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >Lingkar Kerja</a
          >
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >Qebunku</a
          >
        </div>

        <!-- Container Center -->
        <div
          class="flex flex-col justify-start items-start mt-6 md:mt-[65px] md:mr-[50px]">
          <h6 class="font-bold text-lg">Company</h6>
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >About Us</a
          >
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]">Jobs</a>
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]">Blog</a>
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]">FAQ</a>
        </div>

        <!-- Container Left -->
        <div
          id="kontak"
          class="flex flex-col justify-start items-start mt-6 md:mt-[65px] md:mr-[20px]">
          <h6 class="font-bold text-lg">Support & Sales</h6>
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >(+62)817-0364-8888</a
          >
          <a href="#" class="mt-3 text-[#616161] hover:text-[#FFB800]"
            >Hello@qatros.com</a
          >
        </div>
      </div>
    </div>
    <br />
    <div class="h-[36px] bg-[#FFB800]">
      <p class="text-white text-center text-xs pt-2">
        ©{{ new Date().getFullYear() }} PT. Qatros Teknologi Nusantara
      </p>
    </div>
  </div>
</template>
