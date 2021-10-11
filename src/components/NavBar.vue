<template>
<div id="nav">
    <router-link to="/" id="logo-url">
        <img :src="Logo" :alt="Alt" id="Logo">
    </router-link>
    <router-link to="/">Fazer Pedido</router-link>
    <router-link to="/pedidos">Pedidos</router-link>
</div>
</template>

<script>

export default {
    name: 'NavBar',
    props:{
        Logo: Image,
        Alt: String
    }
}
</script>

<style scoped>
#nav{
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
#nav #logo-url{
    margin: auto;
    margin-left: 0;
}

#Logo{
    width: 42px;
    height: 42px;
}
#nav a{
    color: rgb(255, 208, 0);
    text-decoration: none;
    margin: 12px;
    transition: .5s;
}
#nav a:hover{
    color: #ffff;
}
</style>