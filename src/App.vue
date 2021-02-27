<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <hr>
  <PostList />
  <hr>
  <NewPost />
  <hr>
  <!-- Lifecycle Hooks -->
  <Parent />

</template>

<script>
import PostList from './components/PostList.vue';
import NewPost from './components/NewPost.vue';
import Parent from './components/Parent.vue';

export default {
  name: 'App',
  components: {
    PostList,
    NewPost,
    Parent
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
