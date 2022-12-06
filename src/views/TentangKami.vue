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

    <!-- Section 1 -->
    <div class="flex flex-col pt-[150px] w-full m-auto p-10">
      <h1
        class="text-[28px] md:text-[36px] w-[300px] md:w-[453px] h-[110px] font-bold">
        Founded and established in <span class="text-[#FFB800]">2019</span>
      </h1>
      <p class="mt-2 leading-9">
        <span class="text-[#FFB800]">Qatros Technology Nusantara </span>is a
        tightly knit team experts which offers technology services and
        solutions. We handle consultation, development, and the strategic
        approach.<br />
        As we continue to grow as a leading tech company in
        <span class="text-[#FFB800]">Yogyakarta</span>, we declared ourselves as
        a mostreticator that brings innovation of technology from dorp to level
        up everyone's small-medium business needs. <br />
        We work under our proudest culture
        <span class="text-[#FFB800]">"Technology From Ndeso People"</span> as we
        committed to supply high quality technology products and services for
        you. This journey builds on our ever-present dedication to creating
        seamless experience for users and providing them with our technology
        services. <br />
        We believe that with continuous technological innovations that Qatros
        offers,<span class="text-[#FFB800]"
          >there is always a way to solve everyone's problem of their
          needs</span
        >
        . It's not about where we live or where we came from, it’s all about
        commitment to lifelong learning, professional ethic, and dedication of
        work.
      </p>
    </div>

    <!-- Section 2 -->
    <div class="flex flex-col md:flex-row md:mx-16 p-10 md:pt-[90px] pt-12">
      <div class="flex-col md:w-[407px]">
        <h2 class="font-bold text-[30px]">Vision</h2>
        <p class="text-[#717171] mt-2">
          Qatros has a vision to be a world class quality tech company based
          from a rural region which supplies professional services.
        </p>
      </div>
      <div class="md:ml-10 mt-5 md:mt-0 md:w-[443px]">
        <h2 class="font-bold text-[30px]">Mission</h2>
        <p class="text-[#717171] mt-2">
          Qatros armed by experienced technicians and engineers who would bring
          solutions to the table for misc. tech and digital needs with market
          compass (forecast based analysis), latest tech instruments, and
          professional work ethic.
        </p>
      </div>
    </div>

    <!-- Section 3 -->
    <div
      class="flex flex-col md:flex-row md:mx-16 p-10 md:pt-[100px] md:justify-between">
      <div class="w-[300px] md:w-[449px]">
        <h1 class="text-[28px] md:text-[36px] font-bold">
          Some of the people you’ll be
          <span class="text-[#FFB800]">working </span> with
        </h1>
      </div>
      <button
        class="w-[129px] h-[40px] text-[16px] rounded bg-[#FFB800] mt-8 md:mx-40">
        Join With Us
      </button>
    </div>

    <!-- Section 4 -->
    <div
      class="flex flex-col md:flex-row md:justify-around mt-[70px] mb-[150px]">
      <div class="m-auto">
        <img
          src="../assets/images/img-lutvi.png"
          alt="img-lutvi"
          class="w-[250px] md:w-[300px] md:h-[449px]" />
        <div class="mt-4">
          <h3 class="font-bold text-[28px] text-center">Lutvi Rosyady</h3>
          <p class="text-center text-[#717171]">FOUNDER - CEO</p>
        </div>
      </div>
      <div class="m-auto mt-10">
        <img
          src="../assets/images/img-ibnu.png"
          alt="img-ibnu"
          class="w-[250px] md:w-[300px] md:h-[449px]" />
        <div class="mt-4">
          <h3 class="font-bold text-[28px] text-center">Ibnu Fajar Yunardi</h3>
          <p class="text-center text-[#717171]">CO-FOUNDER - CPO</p>
        </div>
      </div>
    </div>

    <img
      src="../assets/images/bg-Kotak.png"
      alt="bg-kotak"
      class="ml-3 w-[50px] md:w-[90px] md:h-[200px]" />
    <Footer class="mt-[-27px] md:mt-[-53px]" />
  </div>
</template>
