<script setup>
// Page meta configuration
definePageMeta({
    layout: "landing"
})

useHead({
    title: 'About Us | Petabiz Nigeria',
    meta: [
        { property: 'og:title', content: 'About Us | Petabiz Nigeria - Human Capital Development Excellence' },
        { property: 'og:description', content: 'Learn about Petabiz Nigeria, Nigeria\'s leading human capital development company. Meet our Gallup-certified coaches and discover our mission to build strengths-based cultures.' },
        { property: 'og:image', content: '/petabiz-about-og.jpg' },
        { name: 'twitter:card', content: 'summary_large_image' }
    ]
});
</script>

<template>
    <div class="min-h-screen bg-white">

        <!-- Navbar Strip - Fixed at top with higher z-index -->
        <div class="fixed top-0 left-0 right-0 h-28 bg-gray-900 z-40"></div>

        <!-- Hero Section with Image and Text -->
        <section class="relative pt-32 pb-20 bg-gradient-to-br from-blue-50 to-white">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-16 items-center max-w-7xl mx-auto">

                    <!-- Left - Image -->
                    <div class="order-2 lg:order-1">
                        <div class="relative rounded-2xl overflow-hidden shadow-2xl">
                            <img src="~/assets/img/human-capital-dev.avif" alt="Human Capital Development"
                                class="w-full h-auto object-cover" />
                            <div class="absolute inset-0 bg-gradient-to-t from-[#336699]/20 to-transparent"></div>
                        </div>
                    </div>

                    <!-- Right - Text Content -->
                    <div class="order-1 lg:order-2 text-center lg:text-left">
                        <div
                            class="inline-flex items-center px-4 py-2 bg-[#ff6701]/10 rounded-full text-[#336699] font-medium text-sm mb-6">
                            <span class="w-2 h-2 bg-[#ff6701] rounded-full mr-2"></span>
                            About Us
                        </div>

                        <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight">
                            About <span class="text-[#336699]">Petabiz Nigeria</span> Limited
                        </h1>

                        <div class="space-y-4 text-base md:text-lg text-gray-900 leading-relaxed">
                            <p>
                                Petabiz Nigeria Limited is a human capacity development company interfacing with a
                                globally distinguished Data Research Enterprise - <span
                                    class="font-semibold text-[#336699]">GALLUP</span> and <span
                                    class="font-semibold text-[#336699]">e2GROW</span> whose prime mission is solving
                                the world's challenging problems of human capital development.
                            </p>
                            <p>
                                Petabiz focus is geared towards the accomplishment of <span
                                    class="font-semibold text-[#ff6701]">Performance, Productivity and
                                    Profitability</span>. We guide organisations in creating Strength-Based Culture. We
                                also guide corporate organisations in creating a Culture where engagement is emphasized
                                as participants leverage on linking their talent to competencies.
                            </p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Mission, Vision, Values Section -->
        <section class="py-4 md:py-12 bg-white">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="max-w-6xl mx-auto">

                    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                        <!-- Mission -->
                        <div
                            class="bg-gradient-to-br from-gray-50 to-white rounded-2xl p-8 shadow-lg border border-gray-100">
                            <div class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path
                                        d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z">
                                    </path>
                                </svg>
                            </div>
                            <h2 class="text-2xl font-bold text-gray-900 mb-4">OUR MISSION</h2>
                            <p class="text-base text-gray-900 leading-relaxed">
                                To guide and empower people to discover and develop their natural talent to accomplish
                                excellence in their life endeavours.
                            </p>
                        </div>

                        <!-- Vision -->
                        <div
                            class="bg-gradient-to-br from-gray-50 to-white rounded-2xl p-8 shadow-lg border border-gray-100">
                            <div class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path d="M10 12a2 2 0 100-4 2 2 0 000 4z"></path>
                                    <path fill-rule="evenodd"
                                        d="M.458 10C1.732 5.943 5.522 3 10 3s8.268 2.943 9.542 7c-1.274 4.057-5.064 7-9.542 7S1.732 14.057.458 10zM14 10a4 4 0 11-8 0 4 4 0 018 0z"
                                        clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <h2 class="text-2xl font-bold text-gray-900 mb-4">OUR VISION</h2>
                            <p class="text-base text-gray-900 leading-relaxed">
                                We aspire to be a foremost human capital 'Strength Champion' in west Africa unleashing
                                Excellence to the Development of Individuals, Teams, Organisations, Startups and
                                Business Owners in line with current realties of the global market-place.
                            </p>
                        </div>

                        <!-- Values -->
                        <div
                            class="bg-gradient-to-br from-gray-50 to-white rounded-2xl p-8 shadow-lg border border-gray-100">
                            <div class="w-14 h-14 bg-[#336699] rounded-2xl flex items-center justify-center mb-6">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd"
                                        d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                                        clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <h2 class="text-2xl font-bold text-gray-900 mb-4">OUR VALUES</h2>
                            <p class="text-sm text-gray-900 mb-3">Our Values reflect who we are and what we stand for:
                            </p>
                            <ul class="space-y-2">
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Communication
                                </li>
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Engagement
                                </li>
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Authenticity
                                </li>
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Performance
                                </li>
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Productivity
                                </li>
                                <li class="flex items-center text-base text-gray-900">
                                    <span class="w-1.5 h-1.5 bg-[#ff6701] rounded-full mr-2"></span>
                                    Excellence
                                </li>
                            </ul>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- Quote Strip -->
        <section class="relative bg-[#1a3d5c] py-16 overflow-hidden">
            <div class="absolute inset-0 opacity-10">
                <div class="absolute top-0 left-1/4 w-64 h-64 bg-[#ff6701] rounded-full blur-3xl"></div>
                <div class="absolute bottom-0 right-1/4 w-64 h-64 bg-[#ffa164] rounded-full blur-3xl"></div>
            </div>

            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-white leading-tight">
                        Get the Best Out of Your <span class="text-[#ff6701]">People</span> To
                        Get the Best Out of Your <span class="text-[#ff6701]">Organization</span>
                    </h2>
                </div>
            </div>
        </section>

        <!-- Gallup Research Stats Section -->
        <section class="py-16 bg-gradient-to-r from-[#336699]/5 to-[#ff6701]/5">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">
                <div class="max-w-6xl mx-auto">
                    <div class="bg-white rounded-2xl shadow-xl p-6 md:p-8 border-l-4"
                        :style="{ borderColor: '#ff6701' }">
                        <div class="flex items-start mb-4">
                            <svg class="w-8 h-8 mt-1 mr-3" :style="{ color: '#ff6701' }" fill="currentColor"
                                viewBox="0 0 20 20">
                                <path fill-rule="evenodd"
                                    d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z"
                                    clip-rule="evenodd" />
                            </svg>
                            <h3 class="text-2xl md:text-3xl font-bold text-gray-900" :style="{ color: '#336699' }">
                                Gallup Research: Strengths-Based Impact
                            </h3>
                        </div>
                        <p class="text-gray-900 text-lg md:text-xl leading-relaxed mb-6">
                            Strengths-based training and coaching drive exceptional workplace performance:
                            <span class="font-bold" :style="{ color: '#ff6701' }">23% more engaged staff</span>,
                            <span class="font-bold" :style="{ color: '#10b981' }">7% increase in customer
                                loyalty</span>,
                            and <span class="font-bold" :style="{ color: '#f59e0b' }">29% boost in profits</span>.
                        </p>
                        <div class="mt-6">
                            <NuxtLink to="/contact"
                                class="inline-block px-8 py-3 font-semibold transition-all duration-300 transform hover:scale-105 rounded-lg shadow-lg hover:shadow-xl"
                                :style="{
                                    backgroundColor: '#ff6701',
                                    color: 'white',
                                    border: 'none'
                                }">
                                Let's Connect
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Coaches Section -->
        <section class="py-20 bg-white">
            <div class="container mx-auto px-6 md:px-8 lg:px-12">

                <!-- Section Header -->
                <div class="text-center mb-16">
                    <div
                        class="inline-flex items-center px-4 py-2 bg-[#ff6701]/10 rounded-full text-[#336699] font-medium text-sm mb-6">
                        <span class="w-2 h-2 bg-[#ff6701] rounded-full mr-2"></span>
                        Meet Our Team
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
                        OUR GALLUP CERTIFIED <span class="text-[#336699]">COACHES</span>
                    </h2>
                    <p class="text-lg md:text-xl text-gray-600 max-w-3xl mx-auto">
                        Meet our team of internationally certified Gallup coaches dedicated to transforming
                        organizations through strengths-based development.
                    </p>
                </div>

                <!-- Coaches Grid - 3 equal columns -->
                <div class="max-w-7xl mx-auto">
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                        <!-- James Kola Ladipo -->
                        <div
                            class="bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100 hover:shadow-2xl transition-all duration-300">
                            <div class="h-72 overflow-hidden">
                                <img src="~/assets/img/james-ladipo.png" alt="James Kola Ladipo"
                                    class="w-full h-full object-cover object-top hover:scale-105 transition-transform duration-500" />
                            </div>
                            <div class="p-6 text-center md:text-left">
                                <h3 class="text-2xl font-bold text-gray-900 mb-2">James Kola Ladipo</h3>
                                <p class="text-base font-semibold text-[#336699] mb-4">CEO & First Triple Gallup Coach
                                    in Nigeria</p>

                                <p class="text-gray-600 mb-4 leading-relaxed">
                                    As the CEO of Petabiz Nigeria Limited, James is the first triple Gallup qualified
                                    coach in Nigeria.
                                </p>

                                <div class="mb-4">
                                    <h4 class="font-semibold text-gray-900 mb-2 text-sm uppercase tracking-wider">
                                        Certifications:</h4>
                                    <ul class="space-y-2">
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup-certified BP10 Coach</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup-certified Strength Coach</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup Train-the-Trainer Coach</span>
                                        </li>
                                    </ul>
                                </div>

                                <p class="text-gray-600 text-sm leading-relaxed">
                                    James deploys broad knowledge gained over 20 years of business across Finance &
                                    Accounting, Sales & Marketing, IT and Human Capital. He is a Fellow of ICAN,
                                    Certified SAP FICO consultant, passionate about guiding entrepreneurs to build
                                    successful businesses.
                                </p>
                            </div>
                        </div>

                        <!-- Antoine Carriere -->
                        <div
                            class="bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100 hover:shadow-2xl transition-all duration-300">
                            <div class="h-72 overflow-hidden">
                                <img src="~/assets/img/antoinne.png" alt="Antoine Carriere"
                                    class="w-full h-full object-cover object-center hover:scale-105 transition-transform duration-500" />
                            </div>
                            <div class="p-6 text-center md:text-left">
                                <h3 class="text-2xl font-bold text-gray-900 mb-2">Antoine Carriere</h3>
                                <p class="text-base font-semibold text-[#336699] mb-4">Triple Qualified Gallup Strength
                                    Coach/Trainer</p>

                                <p class="text-gray-600 mb-4 leading-relaxed">
                                    Antoine is a triple qualified Gallup Strength coach/trainer with focus on
                                    strengths-based development, leadership, engagement and personal development.
                                </p>

                                <div class="mb-4">
                                    <h4 class="font-semibold text-gray-900 mb-2 text-sm uppercase tracking-wider">
                                        Certifications:</h4>
                                    <ul class="space-y-2">
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup-certified Strengths Coach</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup-certified Strengths Course
                                                Leader</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Trained Builder Profile 10
                                                Coach/Trainer</span>
                                        </li>
                                    </ul>
                                </div>

                                <p class="text-gray-600 text-sm leading-relaxed">
                                    He holds a Baccalaureate in Arts (communication), Social Sciences (psychology), and
                                    Certificate in Business Administration from University of Ottawa. Antoine
                                    specializes in working with individuals in the pre-launch phase of the
                                    entrepreneurial cycle.
                                </p>
                            </div>
                        </div>

                        <!-- Augustina Kwao-Sarbah -->
                        <div
                            class="bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100 hover:shadow-2xl transition-all duration-300">
                            <div class="h-72 overflow-hidden">
                                <img src="~/assets/img/sarbiah.jpg" alt="Augustina Kwao-Sarbah"
                                    class="w-full h-full object-cover object-center hover:scale-105 transition-transform duration-500" />
                            </div>
                            <div class="p-6 text-center md:text-left">
                                <h3 class="text-2xl font-bold text-gray-900 mb-2">Augustina Kwao-Sarbah</h3>
                                <p class="text-base font-semibold text-[#336699] mb-4">Gallup Certified Strengths Coach
                                </p>

                                <p class="text-gray-600 mb-4 leading-relaxed">
                                    Augustina Kwao-Sarbah is a Gallup qualified coach with expertise across multiple
                                    domains of human capital development.
                                </p>

                                <div class="mb-4">
                                    <h4 class="font-semibold text-gray-900 mb-2 text-sm uppercase tracking-wider">
                                        Certifications:</h4>
                                    <ul class="space-y-2">
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Gallup-certified Strengths Coach</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Certified CliftonStrengths Trainer & HR
                                                Practitioner</span>
                                        </li>
                                        <li class="flex items-start">
                                            <span class="text-[#ff6701] mr-2 text-xs mt-1">●</span>
                                            <span class="text-gray-600 text-sm">Certified NLP Coach (ABNLP)</span>
                                        </li>
                                    </ul>
                                </div>

                                <p class="text-gray-600 text-sm leading-relaxed">
                                    Her professional career spans over 15 years in Banking and academia, covering
                                    Performance Management, Talent Management, and Training & Development. She
                                    specializes in implementing strength-based culture in workplaces and educational
                                    institutions.
                                </p>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<style scoped>
.transition-all {
    transition-property: all;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 300ms;
}

/* Add padding to account for fixed navbar */
section:first-of-type {
    scroll-margin-top: 4rem;
}
</style>