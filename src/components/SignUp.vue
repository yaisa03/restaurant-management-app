<template>
    <img class="logo" src="../assets/Logo.png"/>
    <h1 class="title">Registro</h1>
    <div class="register">
        <input type="text" placeholder="Ingresa tu Nombre" />
        <input type="text" placeholder="Ingresa tu Email" />
        <input type="text" placeholder="Ingresa tu Contraseña" />
        <button>Registrate</button>
    </div>
</template>

<script>
export default {
    name: 'SignUp',
}
</script>

<style>
.logo {
    width: 250px;
}
.title {
    color: rgb(247, 243, 243);
}
.register input {
    width: 300px;
    height: 35px;
    padding-left: 15px;
    display: block;
    margin-bottom: 20px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid white;
    background: none;
    border-radius: 10px;
}
.register button {
    width: 320px;
    height: 35px;
    border: 1px solid white;
    background-color: #121212;
    color: white;
    border-radius: 10px;
}
.register button:hover {
    background-color: white;
    color: #121212;
}
</style>
