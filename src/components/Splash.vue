<template>
<div id="splash">
    <img class="logo" src="../assets/isotipo.png" alt="">
    <h2>Diseño y desarrollo desde los valles de Jujuy</h2>
    <button class="trabajos" type=""><router-link to="/portfolio"></router-link>TRABAJOS</button>
</div>
</template>

<script>
export default {
    name: "Splash",
}
</script>

<style>

.trabajos{
    background: transparent;
    border: solid #000000 2px;
    width: 200px;
    height: 50px;
    border-radius: 10px;
    margin: 20px 0 20px 0;
    font: 100%;
    font-weight: bold;
    cursor: pointer;
    transition: all 200ms ease;
}

.trabajos:hover{
    border: solid #E50051 2px;
    color: #E50051;
}

#splash{
    background: #f4f6ff;
    margin-top: 100px;
    padding-top: 20px;
}
.logo{
    width: 20%;
    height: 20%;
    margin-top: 25px;
    margin-bottom: 40px;
}
</style>