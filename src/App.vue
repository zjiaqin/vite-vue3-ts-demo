<template>
  <div class="container">{{ message }}</div>
  <button @click="change">点击</button>
</template>

<script setup lang="ts">
const message = ref<string>("hello");
const change = () => {
  message.value = "word";
};
</script>

<style lang="less" scoped></style>
