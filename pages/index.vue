<template>
  <v-app>
    <Navbar />
    <Silde />
    <spot />
    <pricing />
  </v-app>
</template>
<script>
import Navbar from '~/components/navbar.vue'
import Silde from '~/components/silde.vue'
import spot from '~/components/spot.vue'
import pricing from '~/components/pricing'
export default {
  components: {
    spot,
    Navbar,
    Silde,
    pricing,
  },
}
</script>
