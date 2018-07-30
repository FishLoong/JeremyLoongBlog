<template>
  <router-view/>
</template>

<script>
export default {
  name: "Spa"
};
</script>

<style>
* {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "仿宋", "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
#spa {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
