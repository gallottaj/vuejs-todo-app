<template>
  <div class="home">
    <h1>{{ message }}</h1>
    <p>{{ task1 }}</p>
    <p>{{ task2 }}</p>
    <p>{{ task3 }}</p>
  </div>
</template>

<style>
</style>

<script>
export default {
  data: function() {
    return {
      message: "Welcome to Vue.js!",
      task1: "This is a new task",
      task2: "This is a new task",
      task3: "This is a new task"
    };
  },
  created: function() {},
  methods: {},
  computed: {}
};
</script>


