<template>
  <div class="ui inverted segment navbar">
    <div class="ui center aligned container">
      <div class="ui large secondary inverted pointing menu compact">
        <router-link to="/about" class='item'>About</router-link>
        <router-link to="/projects" class='item'>Projects</router-link>
        <router-link to="/skills&technologies" class='item'>Skills & Technologies</router-link>
        <router-link to="/education" class='item'>Education</router-link>
        <router-link to="/experience" class='item'>Experience</router-link>
        <a href="https://drive.google.com/file/d/12uFoupud52cgZqXZKjbHutC3mFtOmQ9-/view?usp=sharing" target="_blank" class='item'>Resume</a> 
        <router-link to="/contact" class='item'>Contact</router-link>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style >
</style>
