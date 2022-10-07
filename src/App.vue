<template>
  <div>
    <h1>Universidad Tecnologica  de Tehuacan </h1>
    <hr/>
    <h2>APW</h2>
    <h3>3 B </h3>
    <span v-text = "'hola desde la directiva de  v-text'"> </span>
    <br>
    <span> Hola desde la directiva de  v-text</span>
    <br>
    <span v-text="titulo"> </span>
    <br> Esta es una trasmutacion de texto {{titulo}} ,  con la variable prop  <br>
    
  </div>
</template>

<script>
  export default{
    data: () =>({
      titulo: "hola desde VUE.js",
    }),
  }
</script>









<style scoped>
  div{
    text-align:center;
    margin: 0px 2rem;
  }
</style>