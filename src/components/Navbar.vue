<template>
  <nav
    class="nav px-6 py-8 mx-auto md:flex md:justify-between md:items-center w-full z-50 border shadow bg-[#fefcf5]">
    <div class="flex items-center justify-between">
      <router-link to="/"
        ><img
          src="../assets/images/logo-qatros.png"
          alt="logo-qatros"
          class="w-[180px] h-[35px] md:w-[212px] md:h-[44px]" />
      </router-link>

      <!-- Mobile menu button -->
      <div @click="toggleNav" class="flex md:hidden">
        <button
          type="button"
          class="text-[#FFB800] focus:outline-none focus:text-[#FFB800]">
          <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
            <path
              fill-rule="evenodd"
              d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
    <ul
      :class="showMenu ? 'flex' : 'hidden'"
      class="font-semibold flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0">
      <router-link to="/">
        <li class="text-black hover:text-[#FFB800]">Home</li>
      </router-link>
      <a href="#portofolio" class="text-black hover:text-[#FFB800]">
        Portofolio
      </a>

      <a href="#layanankami" class="text-black hover:text-[#FFB800]"
        >Layanan Kami</a
      >

      <router-link to="/tentang-kami">
        <li class="text-black hover:text-[#FFB800]">Tentang Kami</li>
      </router-link>
      <a href="#blog" class="text-black hover:text-[#FFB800]">Blog</a>

      <button
        class="font-semibold text-[#FFB800] hover:text-white flex bg-white hover:bg-[#FFB800] border-2 border-[#ffb800] w-[150px] h-[45px] rounded-lg mt-6 justify-center items-center">
        Hubungi Kami
      </button>
    </ul>
  </nav>
</template>

<script>
import { ref } from 'vue';
export default {
  setup() {
    let showMenu = ref(false);
    const toggleNav = () => (showMenu.value = !showMenu.value);
    return { showMenu, toggleNav };
  },
};
</script>

<style>
.nav {
  position: fixed;
}
</style>
