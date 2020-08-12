<template>
  <div class="content">
    <div class="content-header">
      <div class="content-header-user">
        <div class="user-notification"></div>
        <div class="user-icon"></div>
        <p class="user-name">Marlene Sasoeur</p>
      </div>
    </div>
    <Corpus></Corpus>
  </div>
</template>

<script>
import Corpus from "./Corpus";
export default {
  components: {
    Corpus,
  },
};
</script>

<style>
.content {
  flex: 5;
  background: rgb(243, 246, 247);
  display: flex;
  flex-direction: column;
}

.content-header {
  height: 70px;
  background: rgb(255, 255, 255);
  display: flex;
  align-items: center;
  justify-content: flex-end;
}

.content-header-user {
  width: 230px;
  height: 100%;
  margin-right: 30px;
  display: flex;
  align-items: center;
  justify-content: flex-end;
}

.user-notification {
  width: 25px;
  height: 25px;
  border: 1px solid;
  margin-right: 10px;
}

.user-icon {
  width: 25px;
  height: 25px;
  border: 1px solid;
  border-radius: 50%;
  margin: 0 10px;
}

.user-name {
  font-size: 13px;
  color: rgb(109, 109, 109);
}
</style>