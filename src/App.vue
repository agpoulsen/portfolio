<template>
  <div class="app">
    <header class='ui black inverted segment'>
      <h1>Alex Poulsen</h1>
      <h3>Software Engineer</h3>
    </header>
    <Navbar/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'App',
  components: {
    'Navbar': Navbar
  }
};
</script>

<style>
header {
  text-align: center;
  margin: 0
}

</style>
