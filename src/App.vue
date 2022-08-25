<template>
  <div id="app">
    <p>{{ $t("main.welcome", { company: "Yedynka DGTL" }) }}</p>
    <LocaleSwicher />
  </div>
</template>

<script>
import LocaleSwicher from "./components/localeSwicher.vue";
export default {
  name: "App",
  components: { LocaleSwicher },
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
