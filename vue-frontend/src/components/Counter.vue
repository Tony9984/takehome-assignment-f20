<template>
  <div>
    <p>I'm a Counter!</p>
    <p>My current value is {{ count }}</p>
    <button v-on:click="count -= 1">Decrement</button>
    <button v-on:click="count += 1">Increment</button>
  </div>
</template>

<script>
export default {
  props: {
    count: Number
  }
};
</script>

<style>
</style>

