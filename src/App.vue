<template>
  <title>Streaming.ee</title>
  <h1>Streaming {{ value }}</h1>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World!"
    };
  }
};
</script>
<style>
  h1 {
    margin: auto;
  width: 50%;
  padding: 30px;
    text-align: center;
  }
 body {
  background-color: #0f1f3d;
  font:
    1.6rem/1.25 "Helvetica Neue",
    Helvetica,
    Arial,
    sans-serif;
  color: #ffffff;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
}
</style>
