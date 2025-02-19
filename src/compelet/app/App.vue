<template>
    <div class="app font-monospace">
      <div class="content">
      <AppInfo />
      
    
      <div class="search-panel">
        <SearchPanel />
        <AppFilter />
      </div>
      <MovieList />
      <MovieAddFrom />
    </div>
   
    </div>
   
  </template>
  <script>
  import AppInfo from '@/compelet/app-info/AppInfo.vue';
  import SearchPanel from '../search-panel/SearchPanel.vue';
  import AppFilter from '../app-filter/AppFilter.vue';
  import MovieList from '../movie-list/MovieList.vue';
  import MovieAddFrom from '../movie-add-from/MovieAddFrom.vue';
  export default {
     
    components: {
      SearchPanel, 
       AppInfo,
       AppFilter,
       MovieList,
       MovieAddFrom
    } 
  
  }
  </script>
  <style>
      .app{
        height: 100vh;
        color: #000;
      }
      .content{
        width: 1000px;
        min-width: 700px;
        background-color: #fff;
        margin: 0px auto;
        padding: 5rem 0;
      }
      .search-panel{
        margin-top:2rem;
        padding: 1.5rem;
        background-color: #fcfaf5;
        box-shadow: 15px 15px 15px rgb(0, 0, 0.15);
      }
  </style>