<template>
  <div id="app">
    <HeaderWebVue />
  <Nuxt />
  <FooterWeb />
  </div>
</template>
<script>
  // Memanggil component sesuai lokasi masing - masing file

import FooterWeb from '../components/Card/FooterWeb.vue'
import HeaderWebVue from '../components/Card/HeaderWeb.vue'
  export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
  HeaderWebVue,
  FooterWeb
  },
  layouts: 'custom'
  }
</script>
