<script>
import AppHeader from "./components/AppHeader.vue";
import AppSearch from "./components/AppSearch.vue";
import CharacterList from "./components/CharacterList.vue";
import CharacterList from "./components/CharacterList.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppSearch,
    CharacterList,
  },
};
</script>

<template>
  <AppHeader />
  <main>
    <AppSearch />
    <CharacterList />
  </main>
</template>

<style lang="scss">
@use "./styles/general";
</style>