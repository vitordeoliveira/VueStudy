<template>
  <div class="navigation">
    <div class="logo">
      <div class="logo-img">
        <img src="../../../assets/logo.png" />
      </div>
    </div>
    <div class="item">
      <div class="item-icon"></div>
      <p>Dashboard</p>
    </div>
    <div class="item">
      <div class="item-icon"></div>
      <p>Relatório</p>
    </div>
    <div class="item">
      <div class="item-icon"></div>
      <p>Usuários</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.navigation {
  position: relative;
  flex: 1;
  min-width: 260px;
  padding-left: 35px;
  box-shadow: 1px 1px 10px lightgray;
  background: rgb(255, 255, 255);
}

.logo {
  height: 70px;
  border-bottom: 1px solid lightgray;
  display: flex;
  align-items: center;
  justify-content: center;
}

.logo-img {
  width: 130px;
  height: 50px;
}

.logo-img img {
  width: 100%;
}

.item-icon {
  border: 1px solid;
  width: 25px;
  height: 25px;
  margin: 15px;
}

.item {
  display: flex;
  height: 55px;
  border-bottom: 1px solid lightgray;
  color: gray;
  align-items: center;
  padding-left: 4px;
  font-weight: bold;
  justify-content: flex-start;
  font-size: 16px;
}

.item:hover {
  padding-left: 0;
  border-left: 4px solid rgb(167, 70, 70);
  color: rgb(167, 70, 70);
}
</style>