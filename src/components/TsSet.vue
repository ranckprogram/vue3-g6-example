<template>
  <div>name: {{current.name}}</div>
  <div>age: {{current.age}}</div>
</template>


<script setup lang="ts">
import { reactive, defineProps } from "vue";

// interface User {
//   name: String,
//   age: Number,
// }

const props = defineProps<{
  foo: string;
  bar?: number;
}>();

console.log(props);
const current = reactive({
  name: "ranck",
  age: 29,
});

current.name = "dd";
</script>