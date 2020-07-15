<template>
  <div>
    <b-container class="mt-4">
      <b-row>
        <b-col col md="4" v-for="movie in movies" :key="movie.index">
          <MovieCard :movie="movie" />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import MovieCard from "@/components/MovieCard";
import movies from "@/data/movies.json";

export default {
  components: {
    MovieCard
  },
  data() {
    return {
      movies: movies
    };
  }
};
</script>

<style lang="scss" scoped>
</style>
