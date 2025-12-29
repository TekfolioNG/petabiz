<script setup>
// Page meta configuration
definePageMeta({
    layout: "landing"
})

useHead({
    title: 'Coaching - Growth-Focused Leader',
    meta: [
        { property: 'og:title', content: 'Coaching - Growth-Focused Leader' },
        { property: 'og:description', content: 'Equip leaders with essential skills through our Growth-Focused Leader program. Drive engagement, development, and organizational success.' },
        { property: 'og:image', content: '/coaching-og.jpg' },
        { property: 'og:image:width', content: '1200' },
        { property: 'og:image:height', content: '630' },
        { property: 'og:image:alt', content: 'Growth-Focused Leader Coaching' },
        { name: 'twitter:card', content: 'summary_large_image' },
        { name: 'twitter:title', content: 'Coaching - Growth-Focused Leader' },
        { name: 'twitter:description', content: 'Transform your leadership with our Growth-Focused Leader program.' },
        { name: 'twitter:image', content: '/coaching-og.jpg' }
    ],
    link: [
        { rel: 'canonical', href: 'https://botintegrated.com/coaching' }
    ],
});
</script>

<template>
    <div
        class="min-h-screen bg-gradient-to-br from-blue-50 via-white to-indigo-50 dark:from-gray-900 dark:via-gray-800 dark:to-gray-900">

        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden bg-gray-900">
            <div class="absolute inset-0 overflow-hidden">
                <div
                    class="absolute -top-40 -right-40 w-80 h-80 rounded-full bg-gradient-to-br from-blue-400/20 to-indigo-300/20">
                </div>
                <div
                    class="absolute -bottom-40 -left-40 w-80 h-80 rounded-full bg-gradient-to-br from-purple-400/20 to-blue-400/20">
                </div>
            </div>

            <div class="relative container mx-auto px-8 lg:px-16 xl:px-20 2xl:px-32">
                <div class="max-w-4xl mx-auto text-center">
                    <div
                        class="inline-flex items-center px-4 py-2 bg-blue-400/20 rounded-full text-blue-200 font-medium text-sm mb-6">
                        <span class="w-2 h-2 bg-blue-400 rounded-full mr-2"></span>
                        Leadership Development
                    </div>

                    <h1 class="text-5xl lg:text-6xl font-bold text-white mb-6 leading-tight">
                        Growth-Focused Leader
                        <span class="relative block mt-2">
                            <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-indigo-300">
                                Coaching Program
                            </span>
                            <svg class="absolute -bottom-2 left-1/2 transform -translate-x-1/2 w-3/4 h-3"
                                viewBox="0 0 200 12" fill="none">
                                <path d="M2 10C50 5 100 2 198 8" stroke="#60A5FA" stroke-width="3"
                                    stroke-linecap="round" fill="none" />
                            </svg>
                        </span>
                    </h1>

                    <p class="text-xl text-gray-100 mb-8 max-w-3xl mx-auto">
                        Equip leaders with essential knowledge and skills to inspire teams, drive growth, and navigate
                        the evolving demands of today's workplace. Transform management into meaningful coaching.
                    </p>

                    <NuxtLink to="/contact"
                        class="inline-flex items-center px-8 py-4 bg-[#336699] text-white font-bold text-lg rounded-xl hover:shadow-2xl hover:scale-105 transition-all duration-300">
                        Start Your Leadership Journey
                        <svg class="w-5 h-5 ml-2" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd"
                                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                clip-rule="evenodd"></path>
                        </svg>
                    </NuxtLink>
                </div>
            </div>
        </section>

        <!-- GFL Program Overview -->
        <section class="py-20">
            <div class="container mx-auto px-6 text-center md:text-left">
                <div class="max-w-6xl mx-auto">
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                        <div class="space-y-6">
                            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">
                                What is the Growth-Focused Leader (GFL) Program?
                            </h2>
                            <p class="text-lg text-gray-600 dark:text-gray-300">
                                Our Growth-Focused Leader program establishes a clear framework, purpose, and structure
                                that fosters impactful conversations with individuals and teams. This approach inspires,
                                prioritizes, promotes growth, ensures accountability, and enhances collaboration and
                                alignment.
                            </p>
                            <p class="text-lg text-gray-600 dark:text-gray-300">
                                With 70% of employee engagement depending on the manager, the GFL program transforms
                                leaders into coaches who can meet the evolving needs of today's workforce.
                            </p>
                        </div>
                        <div class="relative">
                            <img src="assets/img/strength.png" alt="Growth-Focused Leader Program"
                                class="w-full h-80 object-cover rounded-2xl shadow-lg" />
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- The Changing Workplace -->
        <section class="bg-gradient-to-br from-blue-50 to-indigo-50 dark:from-gray-800 dark:to-gray-900">
            <div class="container mx-auto px-6">
                <div class="max-w-6xl mx-auto">
                    <div class="text-center mb-16">
                        <h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
                            The Changing Demands of Today's Workplace
                        </h2>
                        <p class="text-xl text-gray-600 dark:text-gray-300 max-w-3xl mx-auto">
                            Millennials and Gen Z now make up approximately half of the global workforce, redefining
                            what it means to have a great job and a great life.
                        </p>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
                        <!-- Engagement Statistics -->
                        <div class="bg-white dark:bg-gray-800 rounded-xl p-8 shadow-lg">
                            <div class="text-5xl font-bold text-red-500 mb-4">32%</div>
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-3">
                                Workers Are Engaged
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Down from 36% in 2020. Employee engagement levels have dropped significantly, with
                                younger workers experiencing the most substantial decrease.
                            </p>
                        </div>

                        <div class="bg-white dark:bg-gray-800 rounded-xl p-8 shadow-lg">
                            <div class="text-5xl font-bold text-amber-500 mb-4">80%</div>
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-3">
                                Teams Fail to Reach Goals
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Organizations not adapting to modern workplace demands are seeing teams struggle to
                                achieve their objectives.
                            </p>
                        </div>
                    </div>

                    <!-- Past vs Future -->
                    <div class="bg-white dark:bg-gray-800 rounded-2xl p-10 shadow-xl">
                        <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-8 text-center">
                            The Past (My Job) vs The Future (My Life)
                        </h3>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                            <div>
                                <h4 class="text-lg font-semibold text-red-600 dark:text-red-400 mb-4">❌ Old Workplace
                                </h4>
                                <ul class="space-y-3 text-gray-600 dark:text-gray-300">
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Working for a paycheck</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Job satisfaction</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Bosses and managers</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Annual reviews</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Focus on weaknesses</span>
                                    </li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="text-lg font-semibold text-green-600 dark:text-green-400 mb-4">✓ New
                                    Workplace</h4>
                                <ul class="space-y-3 text-gray-600 dark:text-gray-300">
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Working with purpose and meaning</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Personal development and growth</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Coaches and mentors</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Ongoing conversations</span>
                                    </li>
                                    <li class="flex items-start">
                                        <span class="mr-2">•</span>
                                        <span>Building on strengths</span>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- The Opportunity -->
        <section class="py-12">
            <div class="container mx-auto px-6">
                <div class="max-w-6xl mx-auto">
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                        <div class="lg:order-2 space-y-6">
                            <h2 class="text-3xl font-bold text-gray-900 dark:text-white text-center md:text-left">
                                The Opportunity: 70% of Engagement Depends on the Manager
                            </h2>
                            <p class="text-lg text-gray-600 dark:text-gray-300 text-center md:text-left">
                                There's a significant opportunity for improvement with structured GFL sessions.
                                Organizations that adapt with our performance-driven program see transformative results.
                            </p>
                            <div class="space-y-4">
                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-blue-100 dark:bg-blue-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">📈</span>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-gray-900 dark:text-white">15% Higher Employee
                                            Engagement</h4>
                                        <p class="text-gray-600 dark:text-gray-300">Strengths-based organizations see
                                            measurably better engagement</p>
                                    </div>
                                </div>
                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-green-100 dark:bg-green-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">💰</span>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-gray-900 dark:text-white">29.4% Higher Profit</h4>
                                        <p class="text-gray-600 dark:text-gray-300">Focus on unique talents drives
                                            bottom-line results</p>
                                    </div>
                                </div>
                                <div class="flex items-start">
                                    <div
                                        class="flex-shrink-0 w-12 h-12 bg-purple-100 dark:bg-purple-900 rounded-lg flex items-center justify-center mr-4">
                                        <span class="text-2xl">🎯</span>
                                    </div>
                                    <div>
                                        <h4 class="font-semibold text-gray-900 dark:text-white">72% Lower Attrition</h4>
                                        <p class="text-gray-600 dark:text-gray-300">In high-turnover organizations,
                                            retention improves dramatically</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="lg:order-1 relative">
                            <img src="assets/img/bank2.jpg" alt="Leadership Coaching Success"
                                class="w-full h-full object-cover rounded-2xl shadow-lg" />
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- What Gen Z & Millennials Want -->
        <section class="py-12 bg-white dark:bg-gray-800">
            <div class="container mx-auto px-6">
                <div class="max-w-4xl mx-auto">
                    <h2 class="text-3xl font-bold text-gray-900 dark:text-white mb-8 text-center">
                        What Today's Workforce Values
                    </h2>
                    <p class="text-lg text-gray-600 dark:text-gray-300 mb-12 text-center">
                        Based on Gallup's data-driven research, here's what Millennials and Generation Z are looking
                        for:
                    </p>

                    <div class="space-y-6">
                        <div
                            class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
                                Purpose Over Paycheck
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                They don't just work for a paycheck – they want a purpose. Their work must have meaning,
                                and they want to work for organizations with a clear mission.
                            </p>
                        </div>

                        <div
                            class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
                                Development Over Satisfaction
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                They're no longer pursuing job satisfaction – they're pursuing development. They want
                                coaches, not bosses.
                            </p>
                        </div>

                        <div
                            class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
                                Ongoing Conversations Over Annual Reviews
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                They don't want annual reviews – they want ongoing conversations about their growth and
                                contribution.
                            </p>
                        </div>

                        <div
                            class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
                                Strengths-Based Recognition
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                They don't want managers who fixate on weaknesses. They constantly ask: "Does this
                                organization value my strengths and my contribution?"
                            </p>
                        </div>

                        <div
                            class="bg-gradient-to-r from-blue-50 to-indigo-50 dark:from-gray-700 dark:to-gray-600 rounded-xl p-6">
                            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
                                It's Not Just a Job; It's Their Life
                            </h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                They want to know if the organization values what they bring and supports their overall
                                life goals.
                            </p>
                        </div>
                    </div>

                    <div class="mt-12 text-center">
                        <p class="text-xl font-semibold text-gray-900 dark:text-white mb-6">
                            Adapting to these preferences with our GFL program is key for organizational success.
                        </p>
                        <NuxtLink to="/contact"
                            class="inline-flex items-center px-8 py-4 bg-[#336699] text-white font-bold text-lg rounded-xl hover:shadow-2xl hover:scale-105 transition-all duration-300">
                            Transform Your Leadership Approach
                            <svg class="w-5 h-5 ml-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd"
                                    d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                                    clip-rule="evenodd"></path>
                            </svg>
                        </NuxtLink>
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