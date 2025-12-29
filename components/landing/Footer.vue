<template>
  <footer class="bg-gray-900 text-white pt-16 pb-8 px-6 sm:px-8">
    <div class="container mx-auto">
      <!-- Main Footer -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
        <!-- Column 1: Logo and About -->
        <div class="flex flex-col items-center md:items-start">
          <NuxtLink to="/">
            <img src="~/assets/img/petabiz-logo.png" alt="Petabiz Nigeria Limited Logo" class="h-14 md:h-16" />
          </NuxtLink>

          <p class="text-gray-300 leading-relaxed mb-6 text-center md:text-left mt-4">
            Petabiz Nigeria Limited is a human capacity development company interfacing with a
            globally distinguished Data Research Enterprise – GALLUP whose prime mission is solving
            the world's challenging problems of human capital development.
          </p>
          <NuxtLink to="/contact"
            class="text-[#D2691E] hover:text-white transition-colors text-sm inline-flex items-center">
            Get in touch today
            <Icon name="heroicons:arrow-right" class="h-4 w-4 ml-1" />
          </NuxtLink>
        </div>

        <!-- Column 2: Our Services -->
        <div class="flex flex-col items-center md:items-center">
          <h3 class="text-lg font-semibold mb-6 text-[#D2691E]">
            Our Services
          </h3>
          <ul class="space-y-3 text-center md:text-left">
            <li>
              <NuxtLink to="/" class="text-gray-300 hover:text-white transition-colors">
                Home
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/about" class="text-gray-300 hover:text-white transition-colors">
                About Us
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/training" class="text-gray-300 hover:text-white transition-colors">
                Training
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/coaching" class="text-gray-300 hover:text-white transition-colors">
                Coaching
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/mentoring" class="text-gray-300 hover:text-white transition-colors">
                Mentoring
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/contact" class="text-gray-300 hover:text-white transition-colors">
                Contact Us
              </NuxtLink>
            </li>
          </ul>
        </div>

        <!-- Column 3: Contact Info -->
        <div class="flex flex-col items-center md:items-start">
          <h3 class="text-lg font-semibold mb-6 text-[#D2691E]">
            Contact Us
          </h3>
          <ul class="space-y-4 text-center md:text-left">
            <li class="flex flex-col md:flex-row items-center md:items-start">
              <div class="flex items-start mb-2 md:mb-0 md:mr-3">
                <Icon name="heroicons:map-pin" class="h-5 w-5 text-[#D2691E] flex-shrink-0 mt-1" />
              </div>
              <div class="text-gray-300 text-sm">
                <strong class="block text-white mb-1">Office Address:</strong>
                77 Awolowo Road, MAN House <br>(4th Floor) Ikeja, Lagos, Nigeria.</br>
              </div>
            </li>
            <li class="flex flex-col md:flex-row items-center md:items-start">
              <div class="flex items-center mb-2 md:mb-0 md:mr-3">
                <Icon name="heroicons:phone" class="h-5 w-5 text-[#D2691E] flex-shrink-0" />
              </div>
              <div class="text-gray-300 text-sm">
                <strong class="block text-white mb-1">Tel:</strong>
                <a href="tel:+2348023267433" class="hover:text-[#D2691E] transition-colors">
                  +234 802 326 7433
                </a>
              </div>
            </li>
            <li class="flex flex-col md:flex-row items-center md:items-start">
              <div class="flex items-center mb-2 md:mb-0 md:mr-3">
                <Icon name="heroicons:envelope" class="h-5 w-5 text-[#D2691E] flex-shrink-0" />
              </div>
              <div class="text-gray-300 text-sm">
                <strong class="block text-white mb-1">E-mail:</strong>
                <a href="mailto:info@petabiz.com" class="hover:text-[#D2691E] transition-colors">
                  info@petabiz.com
                </a>
              </div>
            </li>
            <li class="flex flex-col md:flex-row items-center md:items-start">
              <div class="flex items-center mb-2 md:mb-0 md:mr-3">
                <Icon name="mdi:whatsapp" class="h-5 w-5 text-[#D2691E] flex-shrink-0" />
              </div>
              <div class="text-gray-300 text-sm">
                <strong class="block text-white mb-1">WhatsApp:</strong>
                <a href="https://wa.me/2348023267433" target="_blank" class="hover:text-[#D2691E] transition-colors">
                  Chat with us
                </a>
              </div>
            </li>
          </ul>
        </div>
      </div>

      <!-- Footer Bottom -->
      <div class="border-t border-gray-700 pt-6">
        <div class="flex flex-col md:flex-row justify-between items-center gap-4">
          <div class="order-2 md:order-1 text-gray-400 text-sm text-center">
            © {{ new Date().getFullYear() }} Petabiz Nigeria Ltd. All Rights Reserved.
          </div>

          <div class="order-3 text-gray-400 text-sm text-center md:text-right">
            Website by <a href="https://tekfolio.ng" target="_blank"
              class="text-gray-300 hover:text-[#D2691E] transition-colors">Tekfolio Ltd</a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
// No script needed for this component
</script>