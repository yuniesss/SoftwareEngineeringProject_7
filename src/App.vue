<script>
  export default {
    data() {
    return {
      msg: "Hello world!"
    }
  }
  }
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <p>{{msg }}</p>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
</style>
