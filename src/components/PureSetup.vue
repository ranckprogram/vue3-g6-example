<template>
  <div>1 {{data.data}}</div>
</template>

<script setup>
import { onMounted, reactive } from "vue"

const data = reactive(Object.create({
  data: 1
}))

function getData() {
  data.data = 12;
}

onMounted(() => {
  setTimeout(() => {
    getData()
  }, 2000);
})


</script>
