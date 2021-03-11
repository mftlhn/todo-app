<template>
  <div id="app"></div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Go workout",
          completed: false,
        },
        {
          id: 2,
          title: "Go cooking",
          completed: false,
        },
        {
          id: 3,
          title: "Cleaning up home",
          completed: false,
        },
        {
          id: 4,
          title: "Have some sex",
          completed: false,
        },
        {
          id: 5,
          title: "Play game",
          completed: false,
        },
      ],
    };
  },
};
</script>

<style>
</style>
