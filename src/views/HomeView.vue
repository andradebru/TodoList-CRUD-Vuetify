<template>
  <v-container>
    <h1>ToDo List</h1>
    <div>
      <v-col>
        <h2>LOGIN</h2>

        <v-text-field
          label="Usuário"
          :rules="rules"
          hide-details="auto"
        ></v-text-field>
        <v-text-field label="Senha"></v-text-field>

        <v-btn class="blue ligthen-1">Login</v-btn>
        <!-- @click="vaiParaLogin" -->
      </v-col>
      <!-- <TarefaCard /> -->
    </div>
  </v-container>
</template>

<script>
// import TarefaCard from "../components/TarefaCard.vue";

export default {
  components: {
    // TarefaCard,
  },
  // methods: {
  //   listarTarefas() {
  //     TasksApi.getTasks((data) => {
  //       this.listaDeTarefa = data;
  //     });
  //   },
  //   mostrarCadastro() {
  //     this.form.btn = "Adicionar";
  //     this.exibir.form = true;
  //     this.exibir.lista = false;
  //   },
  //   recebiSalvar(novaTarefa) {
  //     TasksApi.createTask(novaTarefa, () => {
  //       this.listarTarefas();
  //       this.exibir.form = false;
  //       this.exibir.lista = true;
  //     });
  //   },
  //   recebiAlterar(tarefa) {
  //     TasksApi.updateTask(tarefa, () => {
  //       this.listarTarefas();
  //       this.exibir.form = false;
  //       this.exibir.lista = true;
  //     });
  //   },
  //   recebiEditar(tarefaId) {
  //     this.form.btn = "Alterar";
  //     TasksApi.getTask(tarefaId, (task) => {
  //       this.form.id = task.id;
  //       this.form.title = task.title;
  //       this.form.project = task.project;
  //       this.exibir.form = true;
  //       this.exibir.lista = false;
  //     });
  //   },
  // },
  // created() {
  //   this.listarTarefas();
  // },
};
</script>

<style></style>
