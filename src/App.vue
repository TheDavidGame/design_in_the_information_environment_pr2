<template>
  <body>
    <div class="wrapper">
      <headerMain />
      <mainWrapper />
      <underMainWrapper />
      <upperFooter />
      <footerWrapper />
    </div>
  </body>
</template>

<script>
import headerMain from './components/headerMain.vue'
import mainWrapper from './components/mainWrapper.vue'
import underMainWrapper from './components/underMainWrapper.vue'
import upperFooter from './components/upperFooter.vue'
import footerWrapper from './components/footerWrapper.vue'

export default {
  name: 'App',
  components: {
    headerMain,
    mainWrapper,
    underMainWrapper,
    upperFooter,
    footerWrapper
  }
}
</script>

<style>
.wrapper {
  background-image: url(./static/header_background.svg);
  background-repeat: no-repeat;
  background-position: center center;
  background-attachment: fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 960px;
}

body {
  margin: 0;
}
@media (max-width: 375.98px) {
  .wrapper {
    height: 782px;
  }
}
</style>
