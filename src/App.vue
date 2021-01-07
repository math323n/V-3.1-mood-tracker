<template>
  <div
    class="max-w-md m-auto bg-green-100 p-5 border container justify-between"
  >
    <episode-card-list v-if="!addingCard"></episode-card-list>
    <add-form v-else></add-form>
    <add-button class="ml-80" @click="addingCard = !addingCard"></add-button>
  </div>
</template>



<script>
import AddButton from "./components/buttons/addButton.vue";
import EpisodeCardList from "./components/cards/episodeCardList.vue";
import AddForm from "./components/misc/addForm.vue";
export default {
  name: "App",
  components: {
    AddButton,
    EpisodeCardList,
    AddForm,
  },
  data() {
    return {
      addingCard: false,
    };
  },
};
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