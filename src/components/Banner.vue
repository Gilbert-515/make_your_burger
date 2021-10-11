<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
#main-banner{
    background-image: url('/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    display: flex;
    height: 500px;
    align-items: center;
    justify-content: flex-start;
    margin: -50px ;
    margin-bottom: 50px;
}

#main-banner h1{
    color: #ffff;
    font-size: 60px;
    text-align: center;
    background-color: #222;
    padding: 20px 40px;
}
</style>