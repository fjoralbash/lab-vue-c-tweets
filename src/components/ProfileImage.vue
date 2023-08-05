<template>
    <img :src="src" className="profile" alt="profile" />
  </template>
  
  <script setup>
  import { defineProps } from 'vue';
  
  const props = defineProps({
    message: String
  });
  </script>
  
  <style></style>