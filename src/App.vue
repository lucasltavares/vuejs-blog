<template>
  <div class="container">
    <Post></Post>
    <router-view />
  </div>
</template>

<script>
import Post from './components/Post.vue'

export default {
  name: 'App',
  components: {
    Post
  }
}
</script>

<style>
</style>
