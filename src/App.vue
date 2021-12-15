<template>
  <div class="app">
    <header class='ui black inverted segment'>
      <h1>Alex Poulsen</h1>
      <h3>Junior Software Engineer</h3>
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

<style scoped>
header {
  text-align: center;
  margin: 0 auto;
}

h1 {
  font-size: 4rem;
}

h3 {
  font-size: 2rem;
}

header {
  width: 100vw;
}

.container {
  max-width: 50vw;
  margin: 0 auto;
}
</style>
