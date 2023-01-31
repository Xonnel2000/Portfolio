<script>
	import { page } from '$app/stores';

</script>
<!-- Navbar -->
<nav class="relative container mx-auto p-6">
  <!-- Flex container -->
  <div class="flex items-center justify-end md:justify-center">
    <!-- Logo -->
    <div class="pt-2">
      <a href="/">
        <!-- <img src="img/logo.svg" alt="" /> -->
      </a>
    </div>
    <!-- Menu Items -->
    <div class="hidden space-x-6 md:flex text-white">
      <a href="/" class="hover:text-darkGrayishBlue text-white">Home</a>
      <!-- <a href="/users" class="hover:text-darkGrayishBlue">Api call</a> -->
      <!-- <a href="/product/mytest" class="hover:text-darkGrayishBlue">Product</a> -->
      <a aria-current={$page.url.pathname === '/about' ? 'page' : undefined}
				 href="/about" class="hover:text-darkGrayishBlue text-white"
        >About Me</a
      >
      <!-- <a href="#" class="hover:text-darkGrayishBlue">Careers</a> -->
      <!-- <a href="#" class="hover:text-darkGrayishBlue">Community</a> -->
    </div>
    <!-- Button 
    <a
      href="#"
      class="hidden p-3 px-6 pt-2 text-white bg-brightRed rounded-full baseline hover:bg-brightRedLight md:block"
      >Get Started</a
    >-->

    <!-- Hamburger Icon -->
    <button id="menu-btn" class="block hamburger md:hidden focus:outline-none">
      <span class="hamburger-top" />
      <span class="hamburger-middle" />
      <span class="hamburger-bottom" />
    </button>
  </div>

  <!-- Mobile Menu -->
  <div class="md:hidden z-50">
    <div
      id="menu"
      class="absolute flex-col items-center hidden self-end py-8 mt-10 space-y-6 font-bold bg-white sm:w-auto sm:self-center left-6 right-6 drop-shadow-md z-50"
    >
      <a class="text-black" href="/">Home</a>
      <!-- <a href="/product">Product</a> -->
      <a class="text-black" aria-current={$page.url.pathname === '/about' ? 'page' : undefined}
      href="/about">About Me</a>
      <!-- <a href="#">Careers</a> -->
    </div>
  </div>
</nav>
