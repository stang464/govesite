<template>
  <v-app>
    <Navbar />
    <div class="pt-16"><nuxt /></div>
  </v-app>
</template>

<script>
import Navbar from '~/components/navbar.vue'
export default {
  components: {
    Navbar,
  },
}
</script>

<style></style>
