<template>
  <NuxtLayout>
    <v-main class="bg-grey-lighten-2">
      <Header />
      <NuxtPage />
    </v-main>
  </NuxtLayout>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Header from './Globals/Header/Header.vue'
export default defineComponent({
  name: 'App',

  components: {
    Header
  },

  data () {
    return {
      //
    }
  },
})
</script>