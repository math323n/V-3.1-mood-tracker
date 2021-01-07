<template>
  <div class="max-w-md m-auto bg-green-100 p-5 border container justify-between">
    <episode-card-list></episode-card-list>
    <add-button class="ml-80"></add-button>
  </div>
  
</template>


<script>
import AddButton from "./components/buttons/addButton.vue"
import EpisodeCardList from "./components/cards/episodeCardList.vue"
export default {
  name: 'App',
  components: {
    AddButton,
    EpisodeCardList
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
