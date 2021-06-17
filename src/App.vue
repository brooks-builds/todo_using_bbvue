<template>
  <div id="app">
    <Title class="title" sub>Vue Todo</Title>
  </div>
</template>

<script>
import {Title} from "bbvue";

export default {
  components: {
    Title,
  },
};
</script>

<style>
body {
  background-color: black;
}

.title {
  color: white;
}
</style>
