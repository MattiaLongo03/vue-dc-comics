<template>
  <div>
    <HeaderTop></HeaderTop>
    <ContentPage></ContentPage>
  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import ContentPage from '@/components/ContentPage.vue';

export default {
  components: {
    HeaderTop,
    ContentPage,
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
