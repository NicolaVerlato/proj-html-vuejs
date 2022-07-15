<template>
  <div id="app">
    <!-- HEADER -->
    <header>
      <HeaderComponent />
    </header>

    <!-- MAIN -->
    <main>
      <JumboTron/>
    </main>

    <!-- FOOTER -->
    <footer>

    </footer>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboTron
  },
}
</script>

<style lang="scss">
@import './assets/styles/common';
header{
  position: relative;
  z-index: 1;
}
main{
  overflow-x: hidden;
}
</style>
