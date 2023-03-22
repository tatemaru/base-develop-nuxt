<template>
  <v-app id="inspire">
    <MainFrame/>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MainFrame from '@/components/MainFrame.vue'

export default defineComponent({
  name: 'App',

  components: {
    MainFrame,
  },

  data () {
    return {
      //
    }
  },
})
</script>
