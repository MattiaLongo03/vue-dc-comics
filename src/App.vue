<template>
  <div>
    <HeaderTop />
    <ContentPage />
    <CardFilm />
    <BlueLine />
    <Footer_1 />
    <Footer_2 />
  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import ContentPage from '@/components/ContentPage.vue';
import CardFilm from '@/components/CardFilm.vue'
import BlueLine from '@/components/BlueLine.vue';
import Footer_1 from '@/components/Footer_1.vue';
import Footer_2 from '@/components/Footer_2.vue';

export default {
  components: {
    HeaderTop,
    ContentPage,
    CardFilm,
    BlueLine,
    Footer_1,
    Footer_2,
  },
};
</script>

<style lang="scss">
 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
 }
</style>
