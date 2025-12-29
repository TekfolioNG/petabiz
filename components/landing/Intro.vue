<template>
  <!-- Professional services overview section -->
  <section class="relative bg-gradient-to-br from-gray-50 to-white overflow-hidden mt-8">
    <!-- Subtle background elements -->
    <div class="absolute inset-0 z-0 opacity-5">
      <div class="absolute top-1/4 left-1/5 w-96 h-96 rounded-full bg-[#336699]/20 blur-3xl"></div>
      <div class="absolute bottom-1/3 right-1/4 w-64 h-64 rounded-full bg-[#ff6701]/15 blur-2xl"></div>
    </div>

    <!-- Main content container -->
    <div class="container mx-auto px-6 md:px-8 lg:px-12 relative z-10 py-8 md:py-14 lg:py-18">

      <!-- Section header -->
      <div class="text-center mb-12 md:mb-16">
        <div class="flex items-center justify-center mb-6">
          <div class="w-12 h-0.5 bg-[#ff6701] mr-4 hidden md:block"></div>
          <span class="text-base uppercase tracking-wider font-medium text-gray-900">
            Human Capital Development Excellence
          </span>
          <div class="w-12 h-0.5 bg-[#ff6701] ml-4 hidden md:block"></div>
        </div>

        <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight">
          Welcome to <span class="text-[#336699]">Petabiz</span> Nigeria Limited
        </h2>

        <div class="max-w-4xl mx-auto space-y-4 text-gray-900">
          <p class="text-lg md:text-xl leading-relaxed">
            We are a <span class="font-semibold text-gray-900">human capacity development company</span> interfacing
            with
            <span class="font-semibold text-[#336699]">Gallup</span>, a globally distinguished data research enterprise
            whose prime mission is solving the world's challenging problems of human capital development.
          </p>
          <p class="text-base md:text-lg">
            With a focus on strengths-based culture, we deliver transformational solutions in
            <span class="font-semibold text-gray-900">leadership development, team engagement, and organizational
              excellence.</span>
          </p>
          <p class="text-base md:text-lg font-medium text-gray-900">
            Whether you're building high-performing teams, developing transformational leaders, or empowering the next
            generation,
            Petabiz is your trusted partner for creating engaged workplaces and sustainable growth.
          </p>
        </div>
      </div>

      <!-- Service highlights grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8 mb-12 md:mb-16">

        <!-- Training -->
        <div
          class="group bg-white rounded-2xl p-6 md:p-8 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-100 hover:-translate-y-1">
          <div class="flex flex-col items-center text-center space-y-4">
            <div
              class="w-16 h-16 bg-[#336699] rounded-2xl flex items-center justify-center group-hover:scale-110 transition-transform duration-300">
              <Icon name="heroicons:academic-cap" class="w-8 h-8 text-white" />
            </div>
            <div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Training</h3>
              <p class="text-lg text-gray-900 leading-relaxed mb-2">
                High-Performing Teams (HPT) Program
              </p>
              <p class="text-base text-gray-900">
                Build strengths-based culture with engaged employees and exceptional team performance.
              </p>
            </div>
            <NuxtLink to="/training"
              class="text-[#ff6701] font-medium text-sm hover:text-[#336699] transition-colors duration-200 flex items-center">
              Learn More
              <Icon name="heroicons:chevron-right"
                class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform" />
            </NuxtLink>
          </div>
        </div>

        <!-- Coaching -->
        <div
          class="group bg-white rounded-2xl p-6 md:p-8 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-100 hover:-translate-y-1">
          <div class="flex flex-col items-center text-center space-y-4">
            <div
              class="w-16 h-16 bg-[#336699] rounded-2xl flex items-center justify-center group-hover:scale-110 transition-transform duration-300">
              <Icon name="heroicons:user-group" class="w-8 h-8 text-white" />
            </div>
            <div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Coaching</h3>
              <p class="text-lg text-gray-900 leading-relaxed mb-2">
                Growth-Focused Leader (GFL) Program
              </p>
              <p class="text-base text-gray-900">
                Develop transformational leadership habits using CliftonStrengths and e2grow methodologies.
              </p>
            </div>
            <NuxtLink to="/coaching"
              class="text-[#ff6701] font-medium text-sm hover:text-[#336699] transition-colors duration-200 flex items-center">
              Learn More
              <Icon name="heroicons:chevron-right"
                class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform" />
            </NuxtLink>
          </div>
        </div>

        <!-- Mentoring -->
        <div
          class="group bg-white rounded-2xl p-6 md:p-8 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-100 hover:-translate-y-1">
          <div class="flex flex-col items-center text-center space-y-4">
            <div
              class="w-16 h-16 bg-[#336699] rounded-2xl flex items-center justify-center group-hover:scale-110 transition-transform duration-300">
              <Icon name="heroicons:light-bulb" class="w-8 h-8 text-white" />
            </div>
            <div>
              <h3 class="text-xl font-bold text-gray-900 mb-2">Mentoring</h3>
              <p class="text-lg text-gray-900 leading-relaxed mb-2">
                Youth Empowerment Programs
              </p>
              <p class="text-base text-gray-900">
                Equip emerging leaders with skills, confidence, and strengths for tomorrow's workplace.
              </p>
            </div>
            <NuxtLink to="/mentoring"
              class="text-[#ff6701] font-medium text-sm hover:text-[#336699] transition-colors duration-200 flex items-center">
              Learn More
              <Icon name="heroicons:chevron-right"
                class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform" />
            </NuxtLink>
          </div>
        </div>

      </div>

    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
/* Smooth transitions for all interactive elements */
.transition-all {
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 300ms;
}

.transition-colors {
  transition-property: background-color, border-color, color, fill, stroke;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 200ms;
}

.transition-transform {
  transition-property: transform;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 300ms;
}

/* Enhanced hover effects */
.group:hover .group-hover\:scale-110 {
  transform: scale(1.1);
}

.group:hover .group-hover\:translate-x-1 {
  transform: translateX(0.25rem);
}

/* Mobile responsiveness */
@media (max-width: 640px) {
  .container {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
</style>