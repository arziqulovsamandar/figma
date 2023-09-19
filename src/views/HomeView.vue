<template>
  <div class="home">
    <h1>Home View</h1>
    <router-link to="/about"></router-link>
    <router-link :to="{name:'about', number:'about',params:{name:name,number:number}}">About vew ga otish</router-link>
  </div>
</template>

<script setup>
import { ref } from 'vue';
const name=ref("ali")
const number=ref(23)
</script>
