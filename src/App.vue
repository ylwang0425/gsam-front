<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{
  margin: 0px;
  padding: 0px;
}
#app {
  position : absolute;
  width : 100%;
  height : 100%;
}
</style>
