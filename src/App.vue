<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <h1 class="foo">
      Foobar
    </h1>
  </div>
</template>

<script>

export default {
  name: 'app',
}
</script>

<style>
body {
  background-color: tomato;

  & .foo {
    color: purple;
  }
}
</style>
