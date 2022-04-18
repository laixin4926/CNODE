<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="slideBar"></router-view>
      <router-view name="main"></router-view>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import PostList from "./components/PostList.vue";

export default {
  name: "App",
  components: {
    Header,
    PostList,
  },
};
</script>

<style>
#app {
  background-color: #e1e1e1;
}
.main {
  margin: 0 auto;

  width: 80%;
}
</style>
