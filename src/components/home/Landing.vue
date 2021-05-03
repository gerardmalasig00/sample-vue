<template>
  <div class="landing">
    <h1>This is my Landing</h1>
  </div>
</template>

<script>
    export default {
        name: "Landing"
    }
</script>

<style lang="scss" scoped>
.landing {
  height: 100vh;
  background: linear-gradient(45deg, blue, red);
  display: grid;
  place-items: center;
  color: white;
}
</style>