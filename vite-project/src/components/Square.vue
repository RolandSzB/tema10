<template>
  <div :class="`w-${size} h-${size} bg-${color} rounded-lg relative`">
    <div
      class="w-0 h-0 border-solid border-transparent border-6 absolute border-t-0 border-l-6 bottom-0 left-0 transform rotate-180"
    ></div>
  </div>
</template>

<script>
export default {
  props: {
    color: {
      type: String,
      default: "blue", // default color if none provided
    },
    size: {
      type: String,
      default: "12", // default size if none provided
    },
  },
};
</script>

<style scoped>
/* Import Tailwind CSS utility classes here if not already done in your project */
</style>
