<template>
  <div id="app">
    <Todos />
  </div>
</template>

<script>
import Todos from "./components/Todos";

export default {
  name: "app",
  components: {
    Todos,
  },
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
          title: "Clean up home",
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
