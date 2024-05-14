<template>
  <p v-if="showResults">Reaction time: {{ score }} ms</p>
</template>

<script>
export default {
  props: ['score', 'showResults']
}
</script>
