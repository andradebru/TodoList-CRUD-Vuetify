<template>
  <v-container>
    <v-col>
      <h1>LOGIN</h1>

      <v-text-field
        label="Usuário"
        :rules="rules"
        hide-details="auto"
      ></v-text-field>
      <v-text-field label="Senha"></v-text-field>

      <v-btn class="blue ligthen-1">Login</v-btn>
      <!-- @click="vaiParaLogin" -->
    </v-col>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    rules: [
      (value) => !!value || "É obrigatório entrar com um usuário.",
      (value) => (value && value.length >= 3) || "Min 3 characters",
    ],
  }),
};
</script>
