<template>
  <body>
    <div class="wrapper">
      <headerMain />
      <mainWrapper />
      <underMain />
      <upperFooter />
      <bottomFooter />
    </div>
  </body>
</template>

<script>
import mainWrapper from './components/mainWrapper.vue'
import headerMain from './components/headerMain.vue'
import underMain from './components/underMain.vue'
import upperFooter from './components/upperFooter.vue'
import bottomFooter from './components/bottomFooter.vue'

export default {
  name: 'App',
  components: {
    mainWrapper,
    headerMain,
    underMain,
    upperFooter,
    bottomFooter
  }
}
</script>

<style>
body {
  margin: 0 !important;
}

.wrapper {
  width: 100%;
  margin: 0 auto;
}
</style>
