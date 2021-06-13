<template>
  <v-app>
    <Silde />
    <spot />
    <pricing />
  </v-app>
</template>
<script>
import Silde from '~/components/silde.vue'
import spot from '~/components/spot.vue'
import pricing from '~/components/pricing'
export default {
  components: {
    spot,
    Silde,
    pricing,
  },
}
</script>
