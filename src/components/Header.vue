<script setup>
import { ref, reactive } from "vue";

let dataSearch = reactive({
  type: "",
  value: "",
});

//IMPLEMENTAR FUNÇÃO PARA FILTRAR A PESQUISA
function handleForm(e) {
  e.preventDefault();

  console.log("Validação:", dataSearch.value);
}
</script>

<template>
  <header class="container-header">
    <nav id="content-header">
      <h1 id="logo">Mainôdex</h1>
      <form id="form-header" @submit="handleForm">
        <label for="type-filter">Filtrar por:</label>
        <select
          v-model="dataSearch.type"
          name="type-filter"
          id="type-filter"
          placeholder="filtro"
        >
          <option value="name">Nome</option>
          <option value="type">Tipo</option>
          <option value="species">Espécie</option>
          <option value="id">Id</option>
        </select>

        <input
          v-model="dataSearch.value"
          v-show="dataSearch.type.length > 0"
          type="text"
          id="input-filter"
        />
        <input type="submit" class="btn-search" value="Buscar" />
      </form>
    </nav>
  </header>
</template>

<style scoped>
.container-header {
  display: flex;
  width: 100vw;
  background-color: royalblue;
  color: #fff;
  height: 8vh;
  align-items: center;
  padding-left: 2rem;
}

#content-header {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
  /* background-color: aquamarine; */
}

#form-header {
  display: flex;
  align-items: center;
  width: 50%;
  align-items: center;
  justify-content: end;
  > select {
    outline: none;
  }
}

#input-filter {
  outline: none;
}

.btn-search{
  &:hover{
    cursor: pointer;
  }
}


</style>
