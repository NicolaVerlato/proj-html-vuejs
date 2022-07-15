<template>
  <div id="app">
    <!-- HEADER -->
    <header>
      <HeaderComponent />
    </header>

    <!-- MAIN -->
    <main>
      <JumboTron/>
      <ProductPresentation/>
    </main>

    <!-- FOOTER -->
    <footer>

    </footer>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import JumboTron from './components/JumboTron.vue'
import ProductPresentation from './components/ProductPresentation.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboTron,
    ProductPresentation
  },
}
</script>

<style lang="scss">
@import './assets/styles/common';

</style>
