<template>
  <div>
    <div id="app">{{a}}</div>
    <button @click="a.b.c='Priyam'">Click</button>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      a: {
        b: {
          c: "saksham"
        }
      }
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
