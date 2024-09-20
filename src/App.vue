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
  <div class="overflow-auto">
    <!-- 3) Utilizzo del componente -->
    <AppHeader />
    
    <AppMain/>

    <AppFooter/>
    <div class="d-flex flex-column button-right">
        <button class="p-2 text-secondary border-0 rounded-2 mb-2">

          <i class="fa-solid fa-folder fa-2xl"></i>

          <div>
            Prebuilts
          </div>

        </button>

        <button class="p-2 text-secondary border-0 rounded-2">

          <i class="fa-solid fa-cart-shopping fa-2xl"></i>

          <div>
            Buy Now
          </div>
        </button>
    </div>
  </div>
</template>

<style lang="scss">
@use '../src/assets/scss/main.scss' as *;

// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";

.button-right{
  position: fixed;
  top: 200px;
  right:20px;
        
}
</style>
