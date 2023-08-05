<template>
    <div>
      <span> {{ timestamp }} </span>
    </div>
  </template>
  
  <script setup>
  import { defineProps } from 'vue';
  
  const props = defineProps({
    timestamp: String
  });
  </script>
  
  <style></style>