<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    master修改111
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    v1.0第二次修改
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class HomeView extends Vue {}
</script>
