<template lang="html">
  <div class="">
    <p>404 - Not Found</p>
    <app-hello></app-hello>
    <app-hello></app-hello>
    <app-hello></app-hello>
    <app-hello></app-hello>
  </div>
</template>

<script>

import HelloWorld from './HelloWorld.vue'
export default {

  components: {
    'app-hello': HelloWorld
  }
}
</script>

<style lang="css">
</style>
