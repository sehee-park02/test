<template>
  <div class="home">
    <Header />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/common/HeaderVue.vue'
import Footer from '@/components/common/FooterVue.vue';

export default {
  name: 'HomeView',
  components: {
    Header,
    Footer
  }
}
</script>
