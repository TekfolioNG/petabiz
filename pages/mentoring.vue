<script setup>
// Page meta configuration
definePageMeta({
    layout: "landing"
})

useHead({
    title: 'Mentoring - Youth Empowerment',
    meta: [
        { property: 'og:title', content: 'Mentoring - Youth Empowerment' },
        { property: 'og:description', content: 'Transform young lives through proven coaching and mentoring programs. Discover talents, develop skills, and empower the next generation.' },
        { property: 'og:image', content: '/mentoring-og.jpg' },
        { property: 'og:image:width', content: '1200' },
        { property: 'og:image:height', content: '630' },
        { property: 'og:image:alt', content: 'Youth Empowerment Mentoring - BOT Integrated' },
        { name: 'twitter:card', content: 'summary_large_image' },
        { name: 'twitter:title', content: 'Mentoring - Youth Empowerment' },
        { name: 'twitter:description', content: 'Nurture young potential through our comprehensive mentoring programs.' },
        { name: 'twitter:image', content: '/mentoring-og.jpg' }
    ],
    link: [
        { rel: 'canonical', href: 'https://botintegrated.com/mentoring' }
    ],
});
</script>

<template>
    <div
        class="min-h-screen bg-gradient-to-br from-emerald-50 via-white to-teal-50 dark:from-gray-900 dark:via-gray-800 dark:to-gray-900">

        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden bg-gray-900">
            <div class="absolute inset-0 overflow-hidden">
                <div
                    class="absolute -top-40 -right-40 w-80 h-80 rounded-full bg-gradient-to-br from-emerald-400/20 to-teal-300/20">
                </div>
                <div
                    class="absolute -bottom-40 -left-40 w-80 h-80 rounded-full bg-gradient-to-br from-green-400/20 to-emerald-400/20">
                </div>
            </div>

            <div class="relative container mx-auto px-8 lg:px-16 xl:px-20 2xl:px-32">
                <div class="max-w-4xl mx-auto text-center">
                    <div
                        class="inline-flex items-center px-4 py-2 bg-emerald-400/20 rounded-full text-emerald-200 font-medium text-sm mb-6">
                        <span class="w-2 h-2 bg-emerald-400 rounded-full mr-2"></span>
                        Youth Development
                    </div>

                    <h1 class="text-5xl lg:text-6xl font-bold text-white mb-6 leading-tight">
                        Youth Empowerment
                        <span class="relative block mt-2">
                            <span class="text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 to-teal-300">
                                Through Mentoring
                            </span>
                            <svg class="absolute -bottom-2 left-1/2 transform -translate-x-1/2 w-3/4 h-3"
                                viewBox="0 0 200 12" fill="none">
                                <path d="M2 10C50 5 100 2 198 8" stroke="#34D399" stroke-width="3"
                                    stroke-linecap="round" fill="none" />
                            </svg>
                        </span>
                    </h1>

                    <p class="text-xl text-gray-100 mb-8 max-w-3xl mx-auto">
                        We believe that every young person has the potential to achieve great things. Our coaching and
                        mentoring programs provide the tools, support, and guidance needed to unlock that potential and
                        build a brighter future.
                    </p>

                    <NuxtLink to="/contact"
                        class="inline-flex items-center px-8 py-4 bg-[#336699] text-white font-bold text-lg rounded-xl hover:shadow-2xl hover:scale-105 transition-all duration-300">
                        Empower Young Minds
                        <svg class="w-5 h-5 ml-2" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd"
                                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                clip-rule="evenodd"></path>
                        </svg>
                    </NuxtLink>
                </div>
            </div>
        </section>

        <!-- Youth Empowerment Programs Overview -->
        <section class="py-20">
            <div class="container mx-auto px-6 md:px-8">
                <div class="max-w-6xl mx-auto">
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                        <div class="space-y-6 px-4 md:px-0 text-center lg:text-left">
                            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">
                                Youth Empowerment Programs
                            </h2>
                            <p class="text-lg text-gray-600 dark:text-gray-300">
                                Over the years, Petabiz Nigeria has been actively engaged in youth coaching and
                                mentoring, demonstrating our commitment to nurturing and developing the potential of
                                young people.
                            </p>
                            <p class="text-lg text-gray-600 dark:text-gray-300">
                                We believe that every young person has the potential to achieve great things, and we are
                                committed to providing them with the tools and support they need to succeed. By
                                investing in young people, we are investing in the future of society and the country.
                            </p>
                        </div>
                        <div class="relative">
                            <img src="assets/img/youth.avif" alt="Youth Empowerment Programs"
                                class="w-full h-80 object-cover rounded-2xl shadow-lg" />
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Impactful Initiatives -->
        <section class="py-12 bg-gradient-to-br from-emerald-50 to-teal-50 dark:from-gray-800 dark:to-gray-900">
            <div class="container mx-auto px-6">
                <div class="max-w-6xl mx-auto">
                    <div class="text-center mb-16">
                        <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
                            Our Impactful Initiatives
                        </h2>
                        <p class="text-xl text-gray-600 dark:text-gray-300 max-w-3xl mx-auto">
                            Our commitment to transforming the lives of young individuals is demonstrated through
                            various collaborative programs and partnerships.
                        </p>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                        <!-- Facebook Collaboration -->
                        <div
                            class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg hover:shadow-xl transition-shadow">
                            <div
                                class="w-16 h-16 bg-gradient-to-br from-emerald-400 to-teal-500 rounded-xl flex items-center justify-center mb-6">
                                <span class="text-3xl">💻</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-3">
                                Facebook Tech Initiative
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Organized a full-day Talent Discovery session for 70 youths in collaboration with
                                Facebook's Tech Initiative for Brightest African Youths as Developers.
                            </p>
                        </div>

                        <!-- LSETF & GIZ -->
                        <div
                            class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg hover:shadow-xl transition-shadow">
                            <div
                                class="w-16 h-16 bg-gradient-to-br from-green-400 to-emerald-500 rounded-xl flex items-center justify-center mb-6">
                                <span class="text-3xl">🎨</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-3">
                                LSETF & GIZ Partnership
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Actively participated in empowering Lagos State youths in creative skills through
                                collaboration with the Lagos State Employment Trust Fund and GIZ.
                            </p>
                        </div>

                        <!-- CLEEN Foundation -->
                        <div
                            class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg hover:shadow-xl transition-shadow">
                            <div
                                class="w-16 h-16 bg-gradient-to-br from-teal-400 to-cyan-500 rounded-xl flex items-center justify-center mb-6">
                                <span class="text-3xl">🤝</span>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-3">
                                CLEEN Foundation Program
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Instrumental in the pilot scheme on Local Government Empowerment using Ajeromi
                                Ifelodun, Adekunle in Lagos, Nigeria, as a test case.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Tools & Methodologies -->
        <section class="py-8">
            <div class="container mx-auto px-6 md:px-8">
                <div class="max-w-6xl mx-auto">
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                        <div class="lg:order-2 space-y-6 px-4 md:px-0 text-center lg:text-left">
                            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">
                                Proven Tools & Methodologies
                            </h2>
                            <p class="text-lg text-gray-600 dark:text-gray-300">
                                Our approach to youth transformation involves the use of proven assessment and
                                development tools designed to unlock potential and build essential life skills.
                            </p>

                            <div class="space-y-6">
                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-emerald-100 dark:bg-emerald-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">🎯</span>
                                    </div>
                                    <div class="text-left">
                                        <h4 class="font-semibold text-gray-900 dark:text-white mb-1">Clifton Strengths
                                            Assessment (Gallup)</h4>
                                        <p class="text-gray-600 dark:text-gray-300">Utilized for talent self-discovery,
                                            helping young people identify and develop their natural strengths.</p>
                                    </div>
                                </div>

                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-green-100 dark:bg-green-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">💼</span>
                                    </div>
                                    <div class="text-left">
                                        <h4 class="font-semibold text-gray-900 dark:text-white mb-1">BP 10 Initiative
                                        </h4>
                                        <p class="text-gray-600 dark:text-gray-300">Tests entrepreneurial traits while
                                            setting the roadmap for successfully creating economic entities to drive the
                                            nation's GDP.</p>
                                    </div>
                                </div>

                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-teal-100 dark:bg-teal-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">🌱</span>
                                    </div>
                                    <div class="text-left">
                                        <h4 class="font-semibold text-gray-900 dark:text-white mb-1">E2Grow</h4>
                                        <p class="text-gray-600 dark:text-gray-300">Activates and nurtures leadership
                                            skills, building team integration capacity in individuals.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="lg:order-1 relative">
                            <img src="assets/img/gfl.jpg" alt="Youth Development Tools"
                                class="w-full h-120 object-cover rounded-2xl shadow-lg" />
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Program Benefits -->
        <section class="py-8 bg-white dark:bg-gray-800">
            <div class="container mx-auto px-6">
                <div class="max-w-4xl mx-auto">
                    <h2 class="text-3xl font-bold text-gray-900 dark:text-white mb-6 text-center">
                        What Our Programs Offer
                    </h2>
                    <p class="text-lg text-gray-600 dark:text-gray-300 mb-10 text-center">
                        Our youth coaching and mentoring programs are designed to help young people develop the skills
                        they need to succeed in life.
                    </p>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div
                            class="bg-gradient-to-br from-emerald-50 to-teal-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <div class="flex items-start">
                                <span class="text-2xl mr-3">🎓</span>
                                <div>
                                    <h3 class="text-lg font-semibold text-gray-900 dark:text-white mb-2">
                                        Skills Development
                                    </h3>
                                    <p class="text-gray-600 dark:text-gray-300">
                                        Comprehensive training in essential life and professional skills needed for
                                        success.
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div
                            class="bg-gradient-to-br from-emerald-50 to-teal-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <div class="flex items-start">
                                <span class="text-2xl mr-3">💡</span>
                                <div>
                                    <h3 class="text-lg font-semibold text-gray-900 dark:text-white mb-2">
                                        Career Exploration
                                    </h3>
                                    <p class="text-gray-600 dark:text-gray-300">
                                        Opportunities to learn about different career paths and discover their passions.
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div
                            class="bg-gradient-to-br from-emerald-50 to-teal-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <div class="flex items-start">
                                <span class="text-2xl mr-3">🚀</span>
                                <div>
                                    <h3 class="text-lg font-semibold text-gray-900 dark:text-white mb-2">
                                        Entrepreneurial Development
                                    </h3>
                                    <p class="text-gray-600 dark:text-gray-300">
                                        Training in entrepreneurial skills to help create future business leaders and
                                        innovators.
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div
                            class="bg-gradient-to-br from-emerald-50 to-teal-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <div class="flex items-start">
                                <span class="text-2xl mr-3">🌍</span>
                                <div>
                                    <h3 class="text-lg font-semibold text-gray-900 dark:text-white mb-2">
                                        Community Engagement
                                    </h3>
                                    <p class="text-gray-600 dark:text-gray-300">
                                        Involvement in community initiatives that build social responsibility and
                                        leadership.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-12 text-center">
                        <div
                            class="bg-gradient-to-r from-emerald-100 to-teal-100 dark:from-gray-700 dark:to-gray-600 rounded-2xl p-8">
                            <p class="text-xl font-semibold text-gray-900 dark:text-white mb-4">
                                By investing in young people, we are investing in the future of society and the country.
                            </p>
                            <NuxtLink to="/contact"
                                class="inline-flex items-center px-8 py-4 bg-[#336699] text-white font-bold text-lg rounded-xl hover:shadow-2xl hover:scale-105 transition-all duration-300">
                                Join Our Youth Programs
                                <svg class="w-5 h-5 ml-2" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd"
                                        d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                        clip-rule="evenodd"></path>
                                </svg>
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA Section -->
        <LandingCta />

    </div>
</template>

<style scoped>
/* Smooth transitions */
* {
    transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 300ms;
}

/* Mobile responsiveness */
@media (max-width: 640px) {
    .container {
        padding-left: 1rem;
        padding-right: 1rem;
    }

    .text-5xl {
        font-size: 2.5rem;
        line-height: 1.1;
    }

    .text-6xl {
        font-size: 3rem;
        line-height: 1.1;
    }
}
</style>