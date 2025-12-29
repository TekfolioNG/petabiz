<template>
    <!-- Lead Coaches Section -->
    <section class="relative bg-gradient-to-br from-gray-50 to-white overflow-hidden">
        <!-- Subtle background elements -->
        <div class="absolute inset-0 z-0 opacity-5">
            <div class="absolute top-1/4 right-1/5 w-96 h-96 rounded-full bg-[#336699]/20 blur-3xl"></div>
            <div class="absolute bottom-1/3 left-1/4 w-64 h-64 rounded-full bg-[#ff6701]/15 blur-2xl"></div>
        </div>

        <div class="container mx-auto px-6 md:px-8 lg:px-12 relative z-10 py-16 md:py-24 lg:py-32">

            <!-- Section header -->
            <div class="text-center mb-12 md:mb-16">
                <div class="flex items-center justify-center mb-6">
                    <div class="w-12 h-0.5 bg-[#ff6701] mr-4 hidden md:block"></div>
                    <span class="text-base uppercase tracking-wider font-medium text-gray-900">
                        World-Class Expertise
                    </span>
                    <div class="w-12 h-0.5 bg-[#ff6701] ml-4 hidden md:block"></div>
                </div>

                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-gray-900 mb-4 leading-tight">
                    Our <span class="text-[#336699]">Lead Coaches</span>
                </h2>
                <p class="text-lg text-gray-900 max-w-2xl mx-auto">
                    Meet our Gallup-certified team of experts dedicated to transforming organizations through
                    strengths-based leadership.
                </p>
            </div>

            <!-- Coaches Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 md:gap-10 max-w-7xl mx-auto mb-12">

                <!-- James Kola Ladipo -->
                <div
                    class="group bg-white rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 border border-gray-100 hover:-translate-y-2">
                    <div class="aspect-square overflow-hidden bg-gray-100">
                        <img src="~/assets/img/james-ladipo.png" alt="James Kola Ladipo"
                            class="w-full h-full object-cover object-top group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <div class="p-6 md:p-8">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">James Kola Ladipo</h3>
                        <p class="text-sm font-semibold text-[#336699] mb-4 uppercase tracking-wide">CEO & Lead
                            Coach/Trainer</p>
                        <p class="text-base text-gray-900 leading-relaxed">
                            The first Triple Gallup Qualified Coach in Nigeria. With over 20 years of business
                            expertise, he holds certifications as a Gallup Certified Strength Coach, Gallup
                            Train-the-Trainer Coach, and Gallup Certified BP10 Coach.
                        </p>
                    </div>
                </div>

                <!-- Antoine Carriere -->
                <div
                    class="group bg-white rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 border border-gray-100 hover:-translate-y-2">
                    <div class="aspect-square overflow-hidden bg-gray-100">
                        <img src="~/assets/img/antoinne.png" alt="Antoine Carriere"
                            class="w-full h-full object-cover object-center group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <div class="p-6 md:p-8">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Antoine Carriere</h3>
                        <p class="text-sm font-semibold text-[#336699] mb-4 uppercase tracking-wide">Lead Coach &
                            Trainer</p>
                        <p class="text-base text-gray-900 leading-relaxed">
                            A Triple Qualified Gallup Strength Coach/Trainer, focuses on strengths-based development,
                            leadership, engagement, and personal growth. Antoine specializes in the pre-launch phase of
                            the entrepreneurial cycle.
                        </p>
                    </div>
                </div>

                <!-- Augustina Kwao-Sarbah -->
                <div
                    class="group bg-white rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 border border-gray-100 hover:-translate-y-2">
                    <div class="aspect-square overflow-hidden bg-gray-100">
                        <img src="~/assets/img/sarbiah.jpg" alt="Augustina Kwao-Sarbah"
                            class="w-full h-full object-cover object-center group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <div class="p-6 md:p-8">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">Augustina Sarbah</h3>
                        <p class="text-sm font-semibold text-[#336699] mb-4 uppercase tracking-wide">Lead Coach &
                            Trainer</p>
                        <p class="text-base text-gray-900 leading-relaxed">
                            A Gallup Certified Strengths Coach, brings over 15 years of experience in banking and
                            academia. She holds certifications as a CliftonStrengths Trainer, HR Practitioner, and
                            Neuro-Linguistic Programming Coach.
                        </p>
                    </div>
                </div>

            </div>

            <!-- Call to action -->
            <div class="text-center">
                <NuxtLink to="/about"
                    class="inline-flex items-center px-8 py-4 bg-[#336699] text-white text-lg font-semibold rounded-xl hover:bg-[#ff6701] transition-all duration-300 transform hover:-translate-y-1 hover:shadow-lg group">
                    <span>See More</span>
                    <Icon name="heroicons:arrow-right"
                        class="ml-3 w-5 h-5 group-hover:translate-x-1 transition-transform" />
                </NuxtLink>
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
    transition-duration: 500ms;
}

/* Mobile responsiveness */
@media (max-width: 640px) {
    .container {
        padding-left: 1rem;
        padding-right: 1rem;
    }
}
</style>