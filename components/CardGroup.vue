<template>
  <div>
    <b-card-group deck class="mt-4" v-for="movie in movies" :key="movie.id">
      <card></card>
    </b-card-group>
  </div>
</template>

<script>
    import axios, * as others from 'axios';
    import Card from "./Card";
    export default {
        data() {
            return {
                movies: null
            }
        },
        mounted() {
          this.getMovies();
        },
        methods: {
            getMovies() {
                axios.get('https://api.themoviedb.org/3/movie/popular?api_key=cdb72ecd87c7e4ac9ee3cad3512f4812')
                    .then(response => {
                        this.movies = response.data.results;
                    })
                    .catch(e => console.log(e))
            }
        },
        name: "CardGroup",
        components: {Card}
    }
</script>

<style scoped>

</style>
