<template>
  <div>
    <b-card
      :title="movie.name"
      :img-src="movie.poster"
      img-alt="img"
      img-top
      tag="article"
      class="mb-4"
    >
      <b-card-text>
        <p>{{ movie.description }}</p>
        <small>{{ movie.genre }}</small>
      </b-card-text>

      <b-button href="#" variant="outline-primary">View Showtimes</b-button>
    </b-card>
  </div>
</template>

<script>
export default {
  props: {
    movie: {
      type: Object
    }
  }
};
</script>

<style lang="scss" scoped>
</style>