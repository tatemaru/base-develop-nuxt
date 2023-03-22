<template>
  <v-card color="grey-lighten-4" flat tile width="100%" class="text-center" height="220px" >
    <v-card-text class="text-h4 py-6">
      Desk Tour
    </v-card-text>
    <v-divider></v-divider>
    <v-card-text class="text-center text-subtitle-2 py-3 px-0">
      <v-tab href="/deskList" prepend-icon="mdi-message-question-outline">デスク一覧</v-tab>
      <v-tab href="/" prepend-icon="mdi-desk">Top</v-tab>
      <v-tab href="/login" prepend-icon="mdi-account">ログイン</v-tab>
    </v-card-text>
    <Keyword/>
    <SuggestChips/>
  </v-card>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import SuggestChips from "./SuggestChips.vue"
import Keyword from "./Keyword.vue"

export default defineComponent({
  name: 'Header',

  components: {
    Keyword,
    SuggestChips
  }
})
</script>