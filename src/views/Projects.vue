<template lang="html">
  <div class="container">

    <div class="ui link cards">

  <sui-card class="card">
    <sui-image src="/touchpoint.png" />
    <sui-card-content>
      <sui-card-header>Touchpoint</sui-card-header>
      <sui-card-description>
        <sui-icon name="info" />
        <strong>FRONTEND UNDER CONSTRUCTION</strong>
        <p>Touchpoint was my final project for General Assembly's Software Engineering Immersive.</p>
        <p>For this project, I wanted to push myself and use a tech-stack I was unfamiliar with.</p>
        <p>Technologies:</p>
        <ul>
          <li>MongoDB</li>
          <li>EspressJS</li>
          <li>NodeJS</li>
          <li>ReactJS</li>
          <li>RESTful APIs</li>
          <li>Authorisation/Authentication via JWTs</li>
        </ul>
    </sui-card-description>
    </sui-card-content>
    <a class="ui bottom attached button" href="https://agpoulsen-final-ga-project.netlify.app/" target="_blank">
     <i class="globe icon"></i>
     Demo Site
   </a>
  </sui-card>

  <sui-card class="card">
    <sui-image src="/gutbucket.png" />
    <sui-card-content>
      <sui-card-header>gutBucket</sui-card-header>
      <sui-card-description>
         <sui-icon name="info" />
         <p>gutBucket was the group project for General Assembly's Software Engineering Immersive.</p>
         <p>A trip planner which enables the user to plan where they will eat out for every meal on a trip.</p>
         <p>Technologies:</p>
         <ul>
           <li>ReactJS</li>
           <li>Google Firebase</li>
           <li>Google Maps & Places API</li>
         </ul>
       </sui-card-description>
    </sui-card-content>
    <a class="ui bottom attached button" href="https://gutbucket-3-rappin-boogalee.web.app/" target="_blank">
     <i class="globe icon"></i>
     Demo Site
   </a>
  </sui-card>

  <sui-card class="card">
    <sui-image src="/dinnr.png" />
    <sui-card-content>
      <sui-card-header>Dinnr</sui-card-header>
      <sui-card-description>
        <sui-icon name="info" />
        <p>Dinnr is a web application that allows friends to find venues in
common that they like on a night out.</p>
        <p> Designed in the matter of popular online dating apps.</p>
        <p>Technologies:</p>
        <ul>
          <li>Ruby on Rails</li>
          <li>PostgreSQL</li>
          <li>Bootstrap</li>
        </ul>
      </sui-card-description>
    </sui-card-content>
    <a class="ui bottom attached button" href="https://seir48project1.herokuapp.com/" target="_blank">
     <i class="globe icon"></i>
     Demo Site
   </a>
  </sui-card>

  <sui-card class="card">
    <sui-image src="/tictactoe.png" />
    <sui-card-content>
      <sui-card-header>Tic Tac Toe</sui-card-header>
      <sui-card-description>
        <sui-icon name="info" />
        <p>The first project of General Assembly's Software Engineering Immersive</p>
        <p>Tic Tac Toe is an online version of the popular two player game.</p>
        <p>Technologies:</p>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>jQuery/JavaScript</li>
        </ul>
        </sui-card-description>
    </sui-card-content>
    <a class="ui bottom attached button" href="https://agpoulsen.github.io/project-0/" target="_blank">
     <i class="globe icon"></i>
     Demo Site
   </a>
  </sui-card>
</div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.container {
  display: flex;
}

.card {
  width: 20rem;
  margin: 2rem;
  display: inline-flex;
}

.card:hover {
  transition: all .2s ease-in-out;
  transform: scale(1.5);
}

li {
  margin: 0.5rem;
}
</style>
