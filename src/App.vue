<template>
  <div id="app">
    <navbar></navbar>
    <pokeguia></pokeguia>
  </div>
</template>

<script>
import PokeGuiaComponent from "./components/Pokeguia.vue";
import NavBarComponent from "./components/Navbar.vue";
export default {
  data() {
    return {
      //
    };
  },
  components: {
    "pokeguia": PokeGuiaComponent,
    "navbar": NavBarComponent,
  }
}
</script>
<style>
#app {
  background-image: url("/src/img/background.jpg");
  font-family: cursive;
}
</style>
