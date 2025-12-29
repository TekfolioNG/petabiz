<template>
    <!-- Gallup Research Quote Section -->
    <section class="relative bg-transparent overflow-hidden">
        <div class="container mx-auto px-6 md:px-8 lg:px-12 py-12 md:py-16">

            <div class="max-w-3xl mx-auto">

                <!-- Gallup Research Card -->
                <div class="bg-gradient-to-br from-[#336699] to-[#1a3d5c] p-6 md:p-8 rounded-2xl border-l-4 shadow-xl"
                    style="border-color: #ff6701;">
                    <div class="flex items-start mb-4">
                        <svg class="w-6 h-6 mt-1 mr-3 flex-shrink-0" style="color: #ff6701" fill="currentColor"
                            viewBox="0 0 20 20">
                            <path fill-rule="evenodd"
                                d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z"
                                clip-rule="evenodd" />
                        </svg>
                        <h3 class="text-xl md:text-2xl font-bold text-white" style="color: #ffa164;">
                            Gallup Research: Strengths-Based Impact
                        </h3>
                    </div>
                    <p class="text-white text-base md:text-lg leading-relaxed mb-6">
                        Strengths-based training and coaching drive exceptional workplace performance:
                        <span class="font-bold" style="color: #ff6701;">23% more engaged staff</span>,
                        <span class="font-bold" style="color: #4ade80;">7% increase in customer loyalty</span>,
                        and <span class="font-bold" style="color: #fbbf24;">29% boost in profits</span>.
                    </p>

                    <!-- Call to Action Button -->
                    <div class="text-center md:text-left">
                        <NuxtLink to="/contact"
                            class="inline-flex items-center px-6 py-3 bg-[#ff6701] text-white text-base md:text-lg font-bold rounded-lg hover:bg-white hover:text-[#336699] transition-all duration-300 transform hover:-translate-y-0.5 shadow-lg group">
                            <span>Let's Connect</span>
                            <Icon name="heroicons:arrow-right"
                                class="ml-2 w-5 h-5 group-hover:translate-x-1 transition-transform" />
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
.transition-all {
    transition-property: all;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 300ms;
}

.transition-transform {
    transition-property: transform;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 300ms;
}

/* Mobile responsiveness */
@media (max-width: 640px) {
    .container {
        padding-left: 1rem;
        padding-right: 1rem;
    }
}
</style>