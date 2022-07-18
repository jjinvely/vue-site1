<template>
  <HeaderSection />
  <SliderSection />
  <ImageSection skill="section" />
  <ImgtextSection skill="section" color="gray" />
  <TextSection />
  <CardSection skill="section" />
  <BannerSection />
  <FooterSection />
</template>

<script>
import HeaderSection from './components/HeaderSection.vue';
import SliderSection from './components/SliderSection.vue';
import ImageSection from './components/ImageSection.vue';
import ImgtextSection from './components/ImgtextSection.vue';
import CardSection from './components/CardSection.vue';
import BannerSection from './components/BannerSection.vue';
import FooterSection from './components/FooterSection.vue';

export default {
  name: 'App',
  components: {
    HeaderSection,
    SliderSection,
    ImageSection,
    ImgtextSection,
    CardSection,
    BannerSection,
    FooterSection,
  },
};
</script>

<style>
@import './App.css';
</style>
