<template>
<div class="section-1">
  <div class="child-1">
    <div class="text-ch-1">
      <div class="name-1">Sharoon Tate</div>
      <div class="perfil">
        <img src="" alt="">
        <p>26courses</p>
      </div>
    </div>
    <div class="button-ch-1"><p>BUTTON</p></div>
  </div>

  <div class="child-2">
    <p>img</p>
    <p>img</p>
  </div>
</div>
<div class="cone">
  <div class="cone-child">
        <h1>{{ msg }}</h1>
    <p>
      Vamos criar um painel administrativo do ZERO !
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
  </div>
    <div class="cone-child">
        <h1>{{ msg }}</h1>
    <p>
      Vamos criar um painel administrativo do ZERO !
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
  </div>
    <div class="cone-child">
        <h1>{{ msg }}</h1>
    <p>
      Vamos criar um painel administrativo do ZERO !
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
