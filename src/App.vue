<template>
  <div id="app">
    <Post title="Post Title" />
    <br />
    <Post title="Post Title 2" />
  </div>
</template>

<script>
import Post from "./components/Post";
export default {
  name: "App",
  components: {
    Post
  }
};
</script>
<style lang="sass">
body
  margin: 0
  padding: 0
  background:
    color: #f3f3f3
  #app
    padding: 25px
</style>
