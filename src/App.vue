<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MyComponent msg='This is My Component ;)'/>
    <YouDoComp1Vue msg="Component Queen"/>
    <YouDoComp2Vue msg1="hahaha" msg2="alright"/>
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue';
import YouDoComp1Vue from './components/YouDoComp1.vue';
import YouDoComp2Vue from './components/YouDoComp2.vue';
export default {
  name: 'App',
  components: {
    MyComponent,
    YouDoComp1Vue,
    YouDoComp2Vue
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
