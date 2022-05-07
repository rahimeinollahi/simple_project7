<template>
  <div class="home">
    <main-head />
    <main-body />
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import MainHead from '../components/HomePage/MainHead.vue'
import MainBody from '../components/HomePage/MainBody.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    MainHead,
    MainBody
  }
}
</script>
