<template>
  <main>
    <div class="jumbotron" />
    <div class="container">
      <h1>current series</h1>
      <Card
        v-for="obj in arrFilm"
        :key="obj.thumb"
        :film="obj"
        class="card"
      />
      <button>load more</button>
    </div>
  </main>
</template>
<script>
import arrFilm from '@/components/dati';
import Card from '@/components/CardFilm.vue';

export default {
  name: 'ContentPage',
  components: {
    Card,
  },
  data() {
    return {
      arrFilm,
    };
  },
};
</script>

<style lang="scss" scoped>
  main{
    width: 100%;
    background-color: black;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .jumbotron{
    width: 100%;
    height: 25rem;
    background-image: url(@/assets/jumbotron.jpg);
    background-position: top;
    background-size: cover;
  }
  .container{
    margin: 4rem 0;
    width: 1200px;
    display: flex;
    flex-wrap: wrap;
    position: relative;
    justify-content: center;
  }

  .card{
    flex: 0 0 calc(100% / 6);
  }

  h1{
    position: absolute;
    color: white;
    background-color: #0282f9;
    text-transform: uppercase;
    padding: 1rem;
    top: -6rem;
    left: -6rem;
  }

  button{
    background-color: #0282f9;
    color: white;
    text-transform: uppercase;
    padding: .5rem 3rem;
    margin: 2rem 0 1rem;
    font-size: 20px;
    font-weight: 500;
  }
</style>
