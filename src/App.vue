<template>
  <div id="app">
    <h1>Alex Poulsen - Software Engineer</h1>
    <div id="navbar">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>|
      <router-link to="/projects">Projects</router-link>|
      <router-link to="/skills&technologies">Skills & Technologies</router-link>|
      <router-link to="/education">Education</router-link>|
      <router-link to="/experience">Experience</router-link>|
      <a href="https://drive.google.com/file/d/12uFoupud52cgZqXZKjbHutC3mFtOmQ9-/view?usp=sharing" target='_blank'>Resume</a>|
      <router-link to="/contact">Contact Me</router-link>

    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
