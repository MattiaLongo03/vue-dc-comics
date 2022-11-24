<template>
  <div>
    <HeaderTop></HeaderTop>
    <ContentPage></ContentPage>
    <BlueLine></BlueLine>
  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import ContentPage from '@/components/ContentPage.vue';
import BlueLine from '@/components/BlueLine.vue';

export default {
  components: {
    HeaderTop,
    ContentPage,
    BlueLine,
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
