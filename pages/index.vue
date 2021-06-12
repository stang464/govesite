<template>
  <v-app>
    <Navbar />
    <Silde />
    <spot />
  </v-app>
</template>
<script>
import Navbar from '~/components/navbar.vue'
import Silde from '~/components/silde.vue'
import spot from '~/components/spot.vue'
export default {
  components: {
    spot,
    Navbar,
    Silde,
  },
}
</script>
