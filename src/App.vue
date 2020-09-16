<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <page-header></page-header>
    <page-body></page-body>
    <page-button></page-button>
    <page-img></page-img>
    <page-footer></page-footer>
    
    
  </div>
</template>

<script>
import PageHeader from "./components/header.vue"
import PageBody from './components/body.vue'
import PageButton from './components/page-button.vue'
import PageImg from './components/page-img.vue'
import PageFooter from "./components/footer.vue"


export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageImg,
    PageButton,
    PageFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
