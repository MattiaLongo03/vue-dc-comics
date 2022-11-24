<template>
  <div>
    <HeaderTop></HeaderTop>
    <ContentPage></ContentPage>
    <BlueLine></BlueLine>
    <Footer_1></Footer_1>
  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import ContentPage from '@/components/ContentPage.vue';
import BlueLine from '@/components/BlueLine.vue';
import Footer_1 from '@/components/Footer_1.vue';

export default {
  components: {
    HeaderTop,
    ContentPage,
    BlueLine,
    Footer_1,
  },
};
</script>

<style lang="scss" scoped>
 *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
 }
</style>
