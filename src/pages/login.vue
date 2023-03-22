<template>
  <v-card width="100%" max-width="800px" class="mx-auto mt-16">
    <v-card-title>
      <v-card-text class="text-center text-h4 py-6">ログイン</v-card-text>
    </v-card-title>
    <v-card-item class="mx-auto my-auto">
      <v-text-field prepend-inner-icon="mdi-account-circle" label="メールアドレス" />
      <v-text-field prepend-inner-icon="mdi-lock" type="password" label="パスワード" />
    </v-card-item>
    <v-card-item class="text-center">
      <v-btn color="grey-lighten-1" class="mx-3">Log in</v-btn>
      <v-btn color="blue-grey-lighten-1" class="mx-3">Sign up</v-btn>
    </v-card-item>
  </v-card>
</template>