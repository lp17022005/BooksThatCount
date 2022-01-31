<template>
  <v-container class="pa-8" fluid>
    <h1 class="h1">Meu perfil</h1>
    <v-form>
      <v-container>
        <v-text-field label="Nome e sobrenome" v-model="nome"></v-text-field>
        <v-text-field label="email" v-model="sobrenome"></v-text-field>
        <v-btn color="success">Salvar</v-btn>
      </v-container>
    </v-form>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      nome: "",
      sobrenome: "",
    };
  },
};
</script>

<style>
</style>