<template>
  <div class="">2 {{adata}}</div>
</template>

<script setup>


import { onMounted, defineProps, toRef } from "vue"


onMounted((data) => {
  console.log(this, data)
})

const props = defineProps({
  adata: String
})

const { adata } = toRef(props)


</script>

<style lang="less" scoped>
</style>