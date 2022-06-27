<template>
  <main>
    <h3>Bem vindo a área de Administração</h3>
    <div class="txtabert">
      <p>Sistema desenvolvido por Brunno Duarte e Lucas Lutf</p>
      <router-link to="/cadastro">
        <button>Acessar</button>
      </router-link>
    </div>
  </main>
</template>
<style scoped>
main {
  position: absolute;
  width: 684px;
  height: 526px;
  left: 378px;
  top: 275px;
  text-align: center;

  background: #656262;
  border-radius: 10px;
}

h3 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 900;
  font-size: 35px;
  line-height: 59px;

  text-align: center;

  color: rgb(255, 255, 255);
}
.txtabert {
  font-family: "Montserrat";
  text-align: center;
  text-decoration: none;
  list-style-type: none;

  color: #000000;
}
.txtabert button {
  position: absolute;
  width: 350px;
  height: 59px;
  left: 161px;
  top: 423px;
  font-family: "Montserrat";
  text-align: center;
  border-radius: 20px;
  background-color: #272424;
  color: #ffffff;
  cursor: pointer;
}
</style>
