<template>
  <div class="ui inverted segment navbar">
    <div class="ui center aligned container">
      <div class="ui large secondary inverted pointing menu compact">
        <router-link to="/about">About</router-link> |
        <router-link to="/projects">Projects</router-link> |
        <router-link to="/skills&technologies">Skills & Technologies</router-link> |
        <router-link to="/education">Education</router-link> |
        <router-link to="/experience">Experience</router-link> |
        <a href="https://drive.google.com/file/d/12uFoupud52cgZqXZKjbHutC3mFtOmQ9-/view?usp=sharing" target="_blank">Resume</a> |
        <router-link to="/contact">Contact</router-link>
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
