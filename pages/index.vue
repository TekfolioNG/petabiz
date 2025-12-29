<script setup lang="ts">
definePageMeta({
  layout: "landing"
});

useHead({
  title: 'Petabiz Nigeria | Succeed with Strength',
  meta: [
    {
      property: 'og:title',
      content: 'Petabiz Nigeria | Human Capital Development & Leadership Excellence'
    },
    {
      property: 'og:description',
      content: 'Transform your organization with strengths-based training, coaching, and mentoring. Partnering with Gallup to build high-performing teams and exceptional leaders across Nigeria.'
    },
    { property: 'og:image', content: '/petabiz-og.jpg' },
    { property: 'og:image:width', content: '1200' },
    { property: 'og:image:height', content: '630' },
    {
      property: 'og:image:alt',
      content: 'Petabiz Nigeria - Human Capital Development & Leadership Excellence'
    },
    { name: 'twitter:card', content: 'summary_large_image' },
    {
      name: 'twitter:title',
      content: 'Petabiz Nigeria | Human Capital Development & Leadership Excellence'
    },
    {
      name: 'twitter:description',
      content: 'Build strengths-based culture with CliftonStrengths training, executive coaching, and youth empowerment programs. Trusted partner for organizational transformation.'
    },
    { name: 'twitter:image', content: '/petabiz-og.jpg' }
  ]
});


</script>

<template>
  <LandingContainer>
    <LandingHero />
    <LandingIntro />
    <LandingPartners />
    <LandingCoaches />
  </LandingContainer>
  <LandingCta />
</template>