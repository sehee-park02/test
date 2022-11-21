<template>
  <div class="home">
    <Header />
    <Sidebar /><Hotimage />
    <ImageList />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/common/HeaderVue.vue'
import Footer from '@/components/common/FooterVue.vue'
import Sidebar from '@/components/common/SidebarVue.vue'
import Hotimage from '@/components/common/HotImageVue.vue'
import ImageList from '@/components/common/ImageListVue.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    Footer,
    Sidebar,
    Hotimage,
    ImageList
  }
}
</script>
