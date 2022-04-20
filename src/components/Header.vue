<template>
  <div class="header">
    <router-link :to="{ name: 'root' }">
      <img src="../assets/cnodejs_light.svg" alt="" />
    </router-link>

    <ul>
      <li>使用技术栈：Vue、Vue-router、jQuery、Axios</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  background-color: #5a5555;
  height: 50px;
}
img {
  max-width: 120px;
  margin-left: 50px;
  margin-top: 10px;
}
ul {
  list-style: none;
  float: right;
  margin: 4px;
}
li {
  display: inline-block;
  padding: 10px 15px;
  color: #ccc;
}
a {
  text-decoration: none;
  color: #ccc;
  font-size: 14px;
}
</style>