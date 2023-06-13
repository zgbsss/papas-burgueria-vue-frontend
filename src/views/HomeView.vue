<script setup>

</script>

<template>
  <main>
    <div class="container">
      <h1>Login</h1> 
      <input type="text" placeholder="email">
      <input type="text" placeholder="senha">
      <button>Entrar</button>
      <p>Entrar como Visitante</p>
    </div>
  </main>
</template>

<style scoped>
  .container {
    display: flex;
    flex-direction: column;
    padding: 20px;
    height: 300px;
    width: 500px;
    background-color: brown;
    color: whitesmoke;
    border-radius: 3px;
  }
  .container input {
    border: none;
    border-radius: 3px;
    margin: 5px;
    height: 50px;
    text-align: center;
    font-size: 20px;
  }
  .container button {
    border: none;
    border-radius: 3px;
    margin: 5px;
    height: 50px;
    text-align: center;
    font-size: 20px;
  }
  h1 {
    text-align: center;
  }
  p {
    text-align: center;
  }
</style>
