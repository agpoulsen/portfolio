<template lang="html">
  <div class="container">

  <i class="massive github icon" @click="openGithub"></i>

  <i class="massive linkedin square icon" @click="openLinkedIn"></i>

  <i class="massive mail outline icon" @click="copyEmailAddress"></i>
  </div>
</template>

<script>
export default {
  name: 'contact',
  methods: {
    openGithub() {
      window.open('https://github.com/agpoulsen', '_blank');
    },
    openLinkedIn() {
      window.open('https://www.linkedin.com/in/alexgpoulsen/', '_blank');
    },
    copyEmailAddress: async function() {
      const email = 'lexpoulsen@gmail.com';
      navigator.clipboard.writeText(email).then(() => {
        alert('Email address copied to clipboard');
      })
    }
  }
}
</script>

<style lang="css" scoped>

.container {
  text-align: center;
  padding: 2em;
}

.massive {
  display: inline-flex;
  padding: 1rem;
  margin: 2rem;
}

.massive:hover {
  color: blue;
  transition: all .2s ease-in-out;
  transform: scale(1.1);
}

</style>
