<template>
  <div class="corpus">
    <div class="corpus-header">
      <div class="corpus-title-icon"></div>
      <h1 class="corpus-title-text">Usuários</h1>
      <div class="corpus-filter">
        <div class="corpus-title-icon"></div>
        <input type="text" placeholder="Pesquisar" />
      </div>
    </div>
    <form class="corpus-form">
      <div class="corpus-form-item">
        <label for="name">Nome completo</label>
        <input id="name" type="text" placeholder="Nome do usuário aqui" />
      </div>
      <div class="corpus-form-item">
        <label for="email">E-mail</label>
        <input id="email" type="text" placeholder="e-mail aqui" />
      </div>
      <div class="corpus-form-item">
        <label for="company" style="color:rgb(106, 178, 236)">Empresa</label>
        <input id="company" type="text" placeholder="Nome da empresa" />
      </div>
      <div class="corpus-form-item">
        <label for="Permissão" style="color:rgb(106, 178, 236)">Permissão</label>
        <select id="Permissão" class="corpus-form-item-select">
          <option disabled selected value>Nome</option>
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="vw">VW</option>
          <option value="audi">Audi</option>
        </select>
      </div>
      <button>Cadastrar usuário</button>
    </form>
    <div class="corpus-list">
      <p class="corpus-list-text">Você ainda não possui nenhum usuário cadastrado</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.corpus {
  flex: 1;
  padding: 30px;
  display: flex;
  flex-direction: column;
}

.corpus-header {
  display: flex;
  flex: 0.8;
  align-items: center;
  position: relative;
  top: -4px;
}

.corpus-title-text {
  margin: 0 20px;
  color: rgb(37, 33, 61);
  font-size: 28px;
}

.corpus-filter {
  position: absolute;
  width: 285px;
  min-height: 45px;
  right: 0;
  display: flex;
  align-items: center;
  background: #fff;
  top: -6px;
  border-radius: 3px;
  box-shadow: 0 2px 2px rgb(189, 189, 189);
}

.corpus-title-icon {
  margin: 0 5px;
  width: 30px;
  height: 30px;
  border: 1px solid;
}

.corpus-form {
  display: flex;
  border-radius: 3px;
  box-shadow: 0 0px 2px rgb(189, 189, 189);
  height: 75px;
  background: #fff;
  margin-top: 10px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-left: 10px;
}

.corpus-list {
  display: flex;
  flex: 5;
  display: flex;
  justify-content: center;
}

.corpus-list-text {
  margin: 50px;
  width: 300px;
  text-align: center;
  font-weight: bold;
  color: rgb(57, 58, 71);
  font-size: 20px;
}

.corpus-form-item {
  display: flex;
  flex-direction: column;
}

.corpus-form-item label {
  color: gray;
  font-size: 11px;
  position: relative;
  top: 5px;
}

.corpus-form-item input {
  border-bottom: 1px solid gray;
  height: 30px;
  width: 180px;
  margin-bottom: 4px;
  padding-bottom: 2px;
}

.corpus-form-item-select {
  border-bottom: 1px solid gray;
  height: 30px;
  width: 180px;
  margin-bottom: 4px;
  padding-bottom: 2px;
  color: gray;
}

.corpus-form button {
  background: rgb(106, 178, 236);
  color: #fff;
  height: 40px;
  width: 130px;
  border-radius: 5px;
  font-size: 15px;
  margin-right: 60px;
}
</style>
