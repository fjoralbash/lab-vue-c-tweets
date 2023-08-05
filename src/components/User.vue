<template>
    <span className="user">
      <span className="name">{{ user.name }}</span>
      <span className="handle">{{ user.handle }}</span>
    </span>
  </template>
  
  <script setup>
import { defineProps } from 'vue';

const props = defineProps({
  user : {
    name:String,
    handle: String
    }
});
</script>