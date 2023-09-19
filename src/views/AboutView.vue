<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h2>My name:{{ route.params.name }}</h2>
    <h3>My age:{{ route.params.number }}</h3>
    <router-link to="/">homega otish</router-link>
  </div>
</template>
<script setup>
import { useRoute } from 'vue-router';
const url=window.location.href.split('/')
const route=useRoute()
</script>