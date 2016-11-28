<template>
  <div id="app">
    <a href="https://http://rubyonrails.org/" target="_blank" title="Rails">
      <img src="./assets/vue.png" height="50">
    </a>
    <a href="https://vuejs.org" target="_blank" title="Vue">
      <img src="./assets/rails.svg" height="50">
    </a>
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello'{{#if_eq lintConfig "airbnb"}};{{/if_eq}}

export default {
  name: 'app',
  components: {
    Hello{{#if_eq lintConfig "airbnb"}},{{/if_eq}}
  }{{#if_eq lintConfig "airbnb"}},{{/if_eq}}
}{{#if_eq lintConfig "airbnb"}};{{/if_eq}}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
