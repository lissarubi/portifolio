<template>
  <a :href="linkDisplay" target="_blank">
    <div class="project">
      <span class="ProjectName">{{ name }}</span>
      <p class="aboutProject">{{ about }}</p>
      <div class="linkProject"></div>
    </div>
  </a>
</template>

<script>
export default {
  name: 'Project',
  props: {
    name: String,
    about: Text,
    link: String,
  },
  computed: {
    linkDisplay() {
      return 'https://github.com/edersonferreira/' + this.link;
    },
  },
};
</script>

<style>
@import '../assets/css/project.css';
</style>
