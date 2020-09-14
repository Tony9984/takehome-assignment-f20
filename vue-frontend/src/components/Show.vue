<template>
  <div>
    <p>{{ name }}</p>
    <Counter v-bind:count="episodes_seen" />
  </div>
</template>

<script>
import Counter from "./Counter.vue";

export default {
  components: {
    Counter
  },
  props: {
    id: Number,
    name: String,
    episodes_seen: Number
  }
};
</script>

<style>
</style>
