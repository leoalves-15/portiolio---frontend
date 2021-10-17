<template>
  <div id="app">
    <Header />
    <hr />
    <Perfil />
   <div id="nav">
      <router-link to="/">Projetos</router-link> |
      <router-link to="/about">About</router-link>
   </div>
    <router-view />
  </div>
</template>
<script>
// @ is an alias to /src
import Header from "./components/Header.vue";
import Perfil from "./components/Perfil.vue";
export default {
  name: "App",
  components: {
    Header,
    Perfil
  },
};
</script>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: #fafafa;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
*{
  padding: 0;
  margin: 0;
  }
hr{
  border-width: 0; 
	height: 1px;
	border-bottom-width: 1px;
  border-color: #e0e0e0;
}
</style>
