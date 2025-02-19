<template >
    <div>
      <ul class="movie-list list-grourp">
        <MovieListItem />
        <MovieListItem />
        <MovieListItem />
      </ul>
    </div>
</template>

<script>
  import MovieListItem from '../movie-list-item/MovieListItem.vue'
  export default{
    components:{
      MovieListItem,
    }
  }
</script>
<style scoped >
    movie-list{
        margin-top:2rem;
        padding: 1.5rem;
        background-color: #fcfaf5;
        box-shadow: 15px 15px 15px rgb(0, 0, 0.15);
    }
    
</style>