<template xmlns="http://www.w3.org/1999/html">
  <h2>Reaction time is</h2>
  <p>{{ score }} ms</p>
</template>

<script>
export default {
  name: "Results",
  props: ['score']
}
</script>

<style scoped>

</style>