<template>
  <div id="app">
    <ValidateQrCode></ValidateQrCode>
  </div>
</template>

<script>
import ValidateQrCode from "./components/validateQrCode";
export default {
  name: 'App',
  components: {
    ValidateQrCode
  }
}
</script>

<style>
  html, body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
  }
  #app {
    width: 100%;
    height: 100%;
  }
</style>
