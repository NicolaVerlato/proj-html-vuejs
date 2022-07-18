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
      <WhatWeDo/>
      <ProductPrices/>
      <CommentComponent/>
      <NewsBlog/>
      <SponsorComponent/>
    </main>

    <!-- FOOTER -->
    <footer>
      <FooterTop/>
      <FooterBottom/>
    </footer>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import JumboTron from './components/JumboTron.vue'
import ProductPresentation from './components/ProductPresentation.vue'
import LearnComponent from './components/LearnComponent.vue'
import ExamplesProj from './components/ExamplesProj.vue'
import WhatWeDo from './components/WhatWeDo.vue'
import ProductPrices from './components/ProductPrices.vue'
import CommentComponent from './components/CommentComponent.vue'
import NewsBlog from './components/NewsBlog.vue'
import SponsorComponent from './components/SponsorComponent.vue'
import FooterTop from './components/FooterTop.vue'
import FooterBottom from './components/FooterBottom.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboTron,
    ProductPresentation,
    LearnComponent,
    ExamplesProj,
    WhatWeDo,
    ProductPrices,
    CommentComponent,
    NewsBlog,
    SponsorComponent,
    FooterTop,
    FooterBottom
  },
}
</script>

<style lang="scss">
@import './assets/styles/common';

</style>
