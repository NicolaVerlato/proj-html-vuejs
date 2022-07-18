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
      <LearnComponent/>
      <ExamplesProj/>
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
import LearnComponent from './components/LearnComponent.vue'
import ExamplesProj from './components/ExamplesProj.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboTron,
    ProductPresentation,
    LearnComponent,
    ExamplesProj
  },
}
</script>

<style lang="scss">
@import './assets/styles/common';

</style>
