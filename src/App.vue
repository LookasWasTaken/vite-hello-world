<script>
import { VueElement } from 'vue';

export default {
  data(){
    return{
      messageHello: "Hello Vue.js!",
      messageBy: "made with 2minutes of time by Lookas"
    }
  }
}
</script>

<template>
<h1>{{messageHello}}</h1>
<h2>{{messageBy}}</h2>
</template>

<style>
</style>
