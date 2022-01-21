<template>
  <div class="hello">
    <TsSet foo="2"/>
  </div>
</template>

<script setup lang="ts">
import TsSet from "./TsSet.vue";
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
