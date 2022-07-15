<template>
  <div id="app">
    <!-- HEADER -->
    <header>
      <HeaderComponent />
    </header>
    <!-- MAIN -->
    <main>
      
    </main>
    <!-- FOOTER -->
    <footer>

    </footer>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent
  },
}
</script>

<style lang="scss">
@import './assets/styles/common';

</style>
