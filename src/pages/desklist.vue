<template>
  <v-main class="grey lighten-2">
    <v-container>
      <v-card class="bg-grey-lighten-2 mx-auto my-0" max-width="1200px">
        <v-row>
          <v-col
            v-for="j in 12"
            :key="`${j}`"
            cols="12"
            md="6"
            sm="6"
            lg="6"
            xl="4"
          >
            <v-sheet height="300"></v-sheet>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
  </v-main>
</template>
<script lang="ts" setup>

</script>