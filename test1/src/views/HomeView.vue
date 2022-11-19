<template>
  <div class="home">
    <Header />
    <Sidebar />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/common/HeaderVue.vue'
import Footer from '@/components/common/FooterVue.vue'
import Sidebar from '@/components/common/SidebarVue.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    Footer,
    Sidebar
  }
}
</script>
