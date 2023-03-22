<template>
  <v-combobox
    class="mx-auto my-0 py-0"
    style="max-width: 1200px;"
    prepend-inner-icon="mdi-magnify"
    density="comfortable"
    label="Combobox"
    :hide-details=true
    :items="['California', 'Colorado', 'Florida', 'Georgia', 'Texas', 'Wyoming']"
  ></v-combobox>
</template>