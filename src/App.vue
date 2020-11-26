<template>
  <div id="app">
    <router-link to="/">Page1</router-link> | 
    <router-link to="/page2">Page2</router-link> 
     <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>

</style>
