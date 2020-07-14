<template>
  <div>
    <b-container class="mt-4">
      <b-row>
        <b-col>
          <MovieCard />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import MovieCard from "@/components/MovieCard";

export default {
  components: {
    MovieCard
  }
};
</script>

<style lang="scss" scoped>
</style>
