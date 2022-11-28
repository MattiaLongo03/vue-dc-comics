<template>
  <div class="card">
    <div class="contents">
      <img
        :src="film.thumb"
        alt="film.series"
      >
      <h2 class="title">
        {{ film.series }}
      </h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardFilm',
  props: {
    film: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    .contents {
      height: 100%;
      img {
        padding: 1rem;
        max-width: 90%;
      }
      h2 {
        font-size: 18px;
        text-transform: uppercase;
        color: white;
      }
    }
  }
</style>
  