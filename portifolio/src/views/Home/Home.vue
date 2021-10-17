<template>
  <div class="home">
    <div class="contain" >
      <Post v-for="project in projects" :key="project.id" :foto="project.url"/>
    </div>
  </div>
</template>
<script>
import Post from '../../components/Post.vue';
//import Post from "../../components/Post.vue";
export default {
  name: "Home",
  components: {
    Post
  },
  data () {
    return {
          projects : []
    }
  },
  methods: {
    fetchTetse() {
      fetch("https://jsonplaceholder.typicode.com/photos")
      .then(r => r.json())
      .then(r => {
      this.projects = r;
      })
    } },
  created(){
    this.fetchTetse();
  } };
</script>
<style src="./home.scss" lang="scss" scoped />
