<script>
// 1) Importazione del componente
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import { store } from './store.js';
export default {
  data() {
    return { 
      store
    }
  },
  // 2) Dichiarazione del componente
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  methods: {
    
  }
}
</script>

<template>
  <div>
    <!-- 3) Utilizzo del componente -->
    <AppHeader />
    
    <AppMain/>

    <AppFooter/>
  </div>
</template>

<style lang="scss">
@use '../src/assets/scss/main.scss' as *;

// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";
</style>
