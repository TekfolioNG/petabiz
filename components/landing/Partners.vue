<template>
    <div>
        <!-- Partners Section -->
        <section class="relative bg-white overflow-hidden">
            <div class="mx-auto px-6 md:px-8 lg:px-12 py-16 md:py-24 lg:py-32 -mt-12 md:-mt-32">

                <!-- Section header -->
                <div class="text-center mb-3 md:mb-4">
                    <div class="flex items-center justify-center mb-6">
                        <div class="w-12 h-0.5 bg-[#ff6701] mr-4 hidden md:block"></div>
                        <span class="text-base uppercase tracking-wider font-medium text-gray-900">
                            Powered By World-Class Tools
                        </span>
                        <div class="w-12 h-0.5 bg-[#ff6701] ml-4 hidden md:block"></div>
                    </div>

                    <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
                        Our <span class="text-[#336699]">Partners</span>
                    </h2>
                </div>

                <!-- Partners Grid -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 md:gap-12 max-w-6xl mx-auto">

                    <!-- Gallup/CliftonStrengths -->
                    <div
                        class="bg-gradient-to-br from-gray-50 to-white rounded-2xl p-8 md:p-10 shadow-lg border border-gray-100 hover:shadow-xl transition-all duration-300">
                        <div class="flex flex-col items-center text-center space-y-6">
                            <div class="w-48 h-32 flex items-center justify-center">
                                <img src="~/assets/img/gallup.png" alt="Gallup Logo"
                                    class="max-w-full max-h-full object-contain" />
                            </div>
                            <div>
                                <h3 class="text-2xl font-bold text-gray-900 mb-4">CliftonStrengths® Assessment</h3>
                                <p class="text-base text-gray-900 leading-relaxed">
                                    CliftonStrengths® is an online assessment tool designed to identify and leverage
                                    individuals' unique strengths.
                                    It helps individuals and teams gain insights into their natural talents, fostering
                                    personal and professional growth.
                                </p>
                                <p class="text-base text-[#336699] font-semibold mt-4">
                                    The Petabiz Nigeria faculty comprises Gallup Strengths-Certified coaches.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- e2grow -->
                    <div
                        class="bg-gradient-to-br from-gray-50 to-white rounded-2xl p-8 md:p-10 shadow-lg border border-gray-100 hover:shadow-xl transition-all duration-300">
                        <div class="flex flex-col items-center text-center space-y-6">
                            <div class="w-48 h-32 flex items-center justify-center">
                                <img src="~/assets/img/e2grow.png" alt="e2grow Logo"
                                    class="max-w-full max-h-full object-contain" />
                            </div>
                            <div>
                                <h3 class="text-2xl font-bold text-gray-900 mb-4">e2grow Digital Platform</h3>
                                <p class="text-base text-gray-900 leading-relaxed">
                                    e2grow enhances organizational productivity through streamlined communication,
                                    collaboration, and task management.
                                    Its user-friendly features and advanced tools empower organizations to achieve
                                    efficiency and success in today's dynamic business landscape.
                                </p>
                                <p class="text-base text-[#336699] font-semibold mt-4">
                                    The Petabiz Nigeria team are e2grow-Certified.
                                </p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Stats Section -->
        <section class="relative bg-[#1a3d5c] w-screen overflow-hidden">
            <!-- Decorative elements -->
            <div class="absolute inset-0 z-0 opacity-10">
                <div class="absolute top-1/4 left-1/5 w-96 h-96 rounded-full bg-white/20 blur-3xl"></div>
                <div class="absolute bottom-1/3 right-1/4 w-64 h-64 rounded-full bg-[#ff6701]/30 blur-2xl"></div>
            </div>

            <div class="w-full px-6 md:px-8 lg:px-12 py-16 md:py-24 lg:py-32 relative z-10">

                <!-- Section header -->
                <div class="text-center mb-12 md:mb-16">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold text-white mb-6 leading-tight">
                        Be Our Next <span class="text-[#ff6701]">Transformed Workplace</span> of the <span
                            class="text-white font-light">Future</span>
                    </h2>
                </div>

                <!-- Stats Grid -->
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 md:gap-10 max-w-7xl mx-auto">

                    <!-- Stat 1 -->
                    <div class="text-center group">
                        <div
                            class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300 hover:-translate-y-1">
                            <div class="text-5xl md:text-6xl font-bold text-[#ff6701] mb-3" ref="stat1">
                                {{ animatedStats.stat1 }}
                            </div>
                            <div class="text-lg md:text-xl text-white font-medium leading-tight">
                                1st Triple Gallup Coach in Nigeria
                            </div>
                        </div>
                    </div>

                    <!-- Stat 2 -->
                    <div class="text-center group">
                        <div
                            class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300 hover:-translate-y-1">
                            <div class="text-5xl md:text-6xl font-bold text-[#ff6701] mb-3" ref="stat2">
                                {{ animatedStats.stat2 }}k+
                            </div>
                            <div class="text-lg md:text-xl text-white font-medium leading-tight">
                                Hours Developing Talents & Leaders
                            </div>
                        </div>
                    </div>

                    <!-- Stat 3 -->
                    <div class="text-center group">
                        <div
                            class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300 hover:-translate-y-1">
                            <div class="text-5xl md:text-6xl font-bold text-[#ff6701] mb-3" ref="stat3">
                                {{ animatedStats.stat3 }}k+
                            </div>
                            <div class="text-lg md:text-xl text-white font-medium leading-tight">
                                CliftonStrengths® Assessments
                            </div>
                        </div>
                    </div>

                    <!-- Stat 4 -->
                    <div class="text-center group">
                        <div
                            class="bg-white/10 backdrop-blur-sm rounded-2xl p-8 border border-white/20 hover:bg-white/15 transition-all duration-300 hover:-translate-y-1">
                            <div class="text-5xl md:text-6xl font-bold text-[#ff6701] mb-3" ref="stat4">
                                {{ animatedStats.stat4 }}+
                            </div>
                            <div class="text-lg md:text-xl text-white font-medium leading-tight">
                                Workplace Training Given in West Africa
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>
    </div>
</template>

<script setup>
import { onBeforeUnmount, onMounted, ref } from 'vue';

const animatedStats = ref({
    stat1: 0,
    stat2: 0,
    stat3: 0,
    stat4: 0
});

const targetStats = {
    stat1: 1,
    stat2: 15,
    stat3: 5,
    stat4: 75
};

let observer = null;
let hasAnimated = false;
let animationFrames = [];

const animateValue = (key, start, end, duration) => {
    const startTime = performance.now();

    const animate = (currentTime) => {
        const elapsed = currentTime - startTime;
        const progress = Math.min(elapsed / duration, 1);

        // Easing function for smooth animation
        const easeOutQuart = 1 - Math.pow(1 - progress, 4);

        animatedStats.value[key] = Math.floor(easeOutQuart * (end - start) + start);

        if (progress < 1) {
            const frameId = requestAnimationFrame(animate);
            animationFrames.push(frameId);
        }
    };

    const frameId = requestAnimationFrame(animate);
    animationFrames.push(frameId);
};

const startAnimation = () => {
    if (hasAnimated) return;
    hasAnimated = true;

    animateValue('stat1', 0, targetStats.stat1, 1000);
    animateValue('stat2', 0, targetStats.stat2, 2000);
    animateValue('stat3', 0, targetStats.stat3, 2000);
    animateValue('stat4', 0, targetStats.stat4, 2500);
};

onMounted(() => {
    // Use setTimeout to ensure DOM is fully ready
    setTimeout(() => {
        // Intersection Observer to trigger animation when stats come into view
        observer = new IntersectionObserver(
            (entries) => {
                entries.forEach((entry) => {
                    if (entry.isIntersecting) {
                        startAnimation();
                    }
                });
            },
            { threshold: 0.2 }
        );

        // Find the stats section
        const statsSection = document.querySelector('.bg-\\[\\#1a3d5c\\]');
        if (statsSection) {
            observer.observe(statsSection);
        }
    }, 100);
});

onBeforeUnmount(() => {
    if (observer) {
        observer.disconnect();
    }
    // Cancel all animation frames
    animationFrames.forEach(frameId => cancelAnimationFrame(frameId));
});
</script>

<style scoped>
.transition-all {
    transition-property: all;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    transition-duration: 300ms;
}

.w-screen {
    width: 100vw;
    margin-left: calc(-50vw + 50%);
}

/* Mobile responsiveness */
@media (max-width: 640px) {
    .container {
        padding-left: 1rem;
        padding-right: 1rem;
    }
}
</style>