<template>
  <div id="app">
    <app-header/>
    <memo-app></memo-app>
  </div>
</template>

<script>

import AppHeader from './components/AppHeader.vue'
import MemoApp from './components/MemoApp.vue'
export default {
  name: 'app',
  components: {
    AppHeader,
    MemoApp
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
@import "./style/reset.css";

#app {
  width: 560px;
  margin: 0 auto; 
}
</style>
