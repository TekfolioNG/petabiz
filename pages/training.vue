<script setup>
// Page meta configuration
definePageMeta({
    layout: "landing"
})

useHead({
    title: 'High-Performing Teams Training | Petabiz Nigeria',
    meta: [
        { property: 'og:title', content: 'High-Performing Teams Training | Petabiz Nigeria' },
        { property: 'og:description', content: 'Transform your teams with our evidence-based HPT program. Structured, data-driven training that delivers measurable impact through CliftonStrengths®.' },
        { property: 'og:image', content: '/petabiz-training-og.jpg' },
        { name: 'twitter:card', content: 'summary_large_image' }
    ]
});
</script>

<template>
    <div class="min-h-screen bg-white">

        <!-- Navbar Strip - Fixed at top -->
        <div class="fixed top-0 left-0 right-0 h-28 bg-gray-900 z-40"></div>

        <!-- Hero Section -->
        <section class="relative pt-48 md:pt-56 bg-gradient-to-br from-blue-50 to-white">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-20 items-center max-w-7xl mx-auto">

                    <!-- Left - Image -->
                    <div class="order-2 lg:order-1">
                        <div class="relative rounded-2xl overflow-hidden shadow-2xl">
                            <img src="~/assets/img/hpt.jpg" alt="High-Performing Teams"
                                class="w-full h-110 object-cover" />
                            <div class="absolute inset-0 bg-gradient-to-t from-[#336699]/20 to-transparent"></div>
                        </div>
                    </div>

                    <!-- Right - Text Content -->
                    <div class="order-1 lg:order-2 text-center lg:text-left">
                        <div
                            class="inline-flex items-center px-4 py-2 bg-[#ff6701]/10 rounded-full text-[#336699] font-medium text-sm mb-6">
                            <span class="w-2 h-2 bg-[#ff6701] rounded-full mr-2"></span>
                            Training Program
                        </div>

                        <h1 class="px-4 text-4xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight">
                            High-Performing Teams <span class="text-[#336699]">(HPT)</span>
                        </h1>

                        <div
                            class="space-y-4 px-4 text-base md:text-lg text-gray-900 leading-relaxed max-w-xl mx-auto lg:mx-0">
                            <p>
                                HPT is a structured, data-driven program that helps teams develop new behaviors that
                                improve their cohesiveness and effectiveness. The program is evidence-based and includes
                                group training, personalized one-on-one coaching, and online micro-learnings that help
                                teams and organizations identify obstacles, optimize collaboration, and continuously
                                progress toward their vision and reaching their full potential.
                            </p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Why HPT Section -->
        <section class="py-24 bg-white">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-20 items-center max-w-7xl mx-auto">

                    <!-- Left - Text Content -->
                    <div class="order-2 lg:order-1 text-center lg:text-left">
                        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">
                            Why <span class="text-[#336699]">HPT?</span>
                        </h2>
                        <div
                            class="space-y-4 text-base md:text-lg text-gray-900 leading-relaxed max-w-xl mx-auto lg:mx-0">
                            <p>
                                High-Performing Teams sessions offers a thoroughly tested, scientifically based approach
                                that delivers measurable impact. The HPT program focuses on tangible, lasting results
                                that enhance team dynamics and overall organizational performance.
                            </p>
                            <p>
                                Unlike many others, HPT isn't just another solution about promoting psychological
                                safety, productivity, or better teamwork—<span class="font-semibold text-[#ff6701]">it's
                                    about stimulating transformative behavioral change within teams</span>. It's a
                                proven
                                method grounded in research and <span
                                    class="font-semibold text-[#336699]">CliftonStrengths®</span>, producing measurable
                                impact.
                            </p>
                        </div>
                    </div>

                    <!-- Right - Image -->
                    <div class="order-2 lg:order-2">
                        <div class="relative rounded-2xl overflow-hidden shadow-2xl">
                            <img src="~/assets/img/teamwork.jpg" alt="Teamwork" class="w-full h-auto object-cover" />
                            <div class="absolute inset-0 bg-gradient-to-t from-[#336699]/20 to-transparent"></div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Key Features Section -->
        <section class="bg-gradient-to-br from-gray-50 to-white mb-16">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="max-w-6xl mx-auto">

                    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                        <!-- Tailored for Teams -->
                        <div
                            class="bg-white rounded-2xl p-8 shadow-lg border border-gray-100 hover:shadow-xl transition-all duration-300 text-center md:text-left">
                            <div
                                class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6 mx-auto md:mx-0">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path
                                        d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3zM6 8a2 2 0 11-4 0 2 2 0 014 0zM16 18v-3a5.972 5.972 0 00-.75-2.906A3.005 3.005 0 0119 15v3h-3zM4.75 12.094A5.973 5.973 0 004 15v3H1v-3a3 3 0 013.75-2.906z">
                                    </path>
                                </svg>
                            </div>
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">Tailored for Teams</h3>
                            <p class="text-base text-gray-900 leading-relaxed mb-4">
                                Sometimes big changes start with small steps. HPT focuses on well-spaced multi-week
                                implementation processes for teams, condensing impactful group trainings, personalized
                                coaching, and online micro-learnings into a compact format.
                            </p>
                            <p class="text-base text-gray-900 leading-relaxed">
                                This means less time spent in live workshops, reducing costs for organizations. The
                                streamlined nature ensures that the program remains accessible to all employees, not
                                just management, without compromising the quality of the experience.
                            </p>
                        </div>

                        <!-- Sustainable -->
                        <div
                            class="bg-white rounded-2xl p-8 shadow-lg border border-gray-100 hover:shadow-xl transition-all duration-300 text-center md:text-left">
                            <div
                                class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6 mx-auto md:mx-0">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd"
                                        d="M4 2a1 1 0 011 1v2.101a7.002 7.002 0 0111.601 2.566 1 1 0 11-1.885.666A5.002 5.002 0 005.999 7H9a1 1 0 010 2H4a1 1 0 01-1-1V3a1 1 0 011-1zm.008 9.057a1 1 0 011.276.61A5.002 5.002 0 0014.001 13H11a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0v-2.101a7.002 7.002 0 01-11.601-2.566 1 1 0 01.61-1.276z"
                                        clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">Sustainable</h3>
                            <p class="text-base text-gray-900 leading-relaxed mb-4">
                                Using the <span class="font-semibold text-[#ff6701]">AIM, REFLECT, HIGH5, COFFEESYNC,
                                    & PROGRESS</span> methodology for team behavioral change and cohesiveness, HPT
                                extends beyond singular interactions.
                            </p>
                            <p class="text-base text-gray-900 leading-relaxed">
                                We prioritize lasting transformation over fleeting "aha" moments, providing your teams
                                with tools and strategies that stand the test of time. HPT's sustainability ensures that
                                the positive changes initiated within your teams become ingrained aspects of your
                                organizational culture.
                            </p>
                        </div>

                        <!-- Scalable -->
                        <div
                            class="bg-white rounded-2xl p-8 shadow-lg border border-gray-100 hover:shadow-xl transition-all duration-300 text-center md:text-left">
                            <div
                                class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6 mx-auto md:mx-0">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path
                                        d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM14 11a1 1 0 011 1v1h1a1 1 0 110 2h-1v1a1 1 0 11-2 0v-1h-1a1 1 0 110-2h1v-1a1 1 0 011-1z">
                                    </path>
                                </svg>
                            </div>
                            <h3 class="text-2xl font-bold text-gray-900 mb-4">Scalable</h3>
                            <p class="text-base text-gray-900 leading-relaxed mb-4">
                                Standardized in content and fully repeatable, HPT is inherently scalable. Whether you
                                have one team or multiple teams across your organization, our program adapts seamlessly.
                            </p>
                            <p class="text-base text-gray-900 leading-relaxed">
                                The <span class="font-semibold text-[#336699]">e2grow platform</span> facilitates
                                transparent project management, making it easy to disseminate the program across various
                                teams. This ensures a consistent, high-quality experience for every team and allows the
                                entire organization to share a common language and behavioral framework across the
                                entire workforce. With HPT, scalability becomes a powerful tool for widespread
                                organizational enhancement.
                            </p>
                        </div>

                    </div>
                </div>
            </div>
        </section>
        <LandingCta />

    </div>
</template>

<style scoped>
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

/* Add padding to account for fixed navbar */
section:first-of-type {
    scroll-margin-top: 4rem;
}
</style>