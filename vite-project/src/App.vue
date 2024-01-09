<template>
  <div>
    <Square color="red" size="16" />
    <Square color="green" size="8" />
    <Square color="yellow" size="20" />
  </div>
</template>

<script>
import Square from "./components/Square.vue";

export default {
  components: {
    Square,
  },
};
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
