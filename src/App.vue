<template>
  <div class="app">
    <HeaderComponent />
    <ContentComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import ContentComponent from './components/ContentComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    ContentComponent
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fffeff;
  background-color: black;
  height: 100vh;
  width: 100%;
}
</style>
