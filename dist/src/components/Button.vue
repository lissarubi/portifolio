<template>
  <a :style="style" :href="link" class="tech" target="_blank">{{ name }}</a>
</template>

<script>
export default {
  name: 'Button',
  props: {
    color: String,
    name: String,
    link: String,
  },
  computed: {
    style() {
      return 'background-color: #' + this.color;
    },
  },
};
</script>

<style>
@import '../assets/css/button.css';
</style>
