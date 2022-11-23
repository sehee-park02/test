<template>
  <div class="about">
    <Signup />
  </div>
</template>

<script>
// @ is an alias to /src
import Signup from '@/components/common/SignupVue.vue'

export default {
  name: 'HomeView',
  components: {
    Signup
  }
}
</script>