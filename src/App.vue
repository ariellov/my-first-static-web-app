<template>
  <div>Streaming {{ value }}</div>
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
  @media screen and (min-width: 620px) {
    [class*="__lg"] {
      font-size: 2.4rem;
    }
  }
</style>
