<template>
  <main>
    <div class="painel">
      <router-link to="/">
        <span>Painel do administrador</span>
      </router-link>
    </div>
  </main>
</template>
<style scoped>
.painel {
  position: absolute;
  width: 1581px;
  height: 145px;
  left: 1px;
  top: 0px;

  background: #474343;
  border-radius: 25px;
}
.painel span {
  position: absolute;
  width: 780px;
  height: 59px;
  left: 40px;
  top: 35px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 900;
  font-size: 35px;
  line-height: 59px;

  text-align: left;

  color: #ffffff;
}
</style>
