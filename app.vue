<script setup lang="ts">
const icons = ['i-mdi-alarm', 'i-mdi-menu', 'i-mdi-account', 'i-mdi-email', 'i-mdi-book']
</script>
<template>
  <div>
    <h1>UNOCSS icons</h1>
    <div v-for="(item, index) in icons" :key="index">
      <div class="flex">
    Name:  {{item}} Icon: <div :class="item"></div>
      </div>
    </div>
  </div>
</template>
