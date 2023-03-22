<template>
  <v-main class="bg-grey-lighten-2">
    <Carousels />
  </v-main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Carousels from '@/components/Parts/Carousels.vue';
export default defineComponent({
  name: 'Top',
  components: {
    Carousels
  },
  setup(){}
})
</script>