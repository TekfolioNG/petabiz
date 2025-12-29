<template>
  <!-- Call to action -->
  <div class="text-center">
    <div
      class="bg-gradient-to-r from-[#336699]/10 to-[#ff6701]/5 rounded-3xl p-8 md:p-12 border border-[#336699]/20 py-24 md:py-18">
      <h3 class="text-2xl md:text-3xl font-bold text-gray-900 mb-4">
        Ready to Build a New Workplace Culture <br>of the Future?</br>
      </h3>
      <p class="text-gray-900 text-lg mb-8 max-w-2xl mx-auto">
        Partner with us to build a strengths-based culture, develop exceptional leaders, and create
        high-performing teams that drive sustainable business results.
      </p>
      <NuxtLink to="/contact"
        class="inline-flex items-center px-8 py-4 bg-[#336699] text-white text-lg font-semibold rounded-xl hover:bg-[#ff6701] transition-all duration-300 transform hover:-translate-y-1 hover:shadow-lg group">
        <span>Get Started Today</span>
        <ArrowRightIcon class="ml-3 w-5 h-5 group-hover:translate-x-1 transition-transform" />
      </NuxtLink>
    </div>
  </div>
</template>

<script setup>
// No script needed for this component
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