<template> 
    <div id="somos">
        <div class="container">
            <h2 class="title-component">Somos</h2>
            <span>Hola mundo! Somos Gabriela y Sergio, hermanxs apasionadxs por comprender nuestra tierra. Decidimos fundar JALLALLA para desarrollar los emprendimientos y conectarlos con el mundo</span>
            <div class="row row-avatar">
                <div class="col-sm-6 avatar">
                    <img class="avatar-img" src="../assets/gab1.jpg" alt="">
                    <div class="avatar-text"><span><b>Gabriela</b><br>Técnica electrónica, actualmente estudio Ingenieria Electrónica en la Universidad Tecnológica Nacional. Desde los 15 diseño en mis tiempos libres, soy muy perfeccionista, independiente para aprender y desde hace tiempo trabajo como freelance en el rubro</span></div>
                </div>
                <div class="col-sm-6 avatar">
                    <img class="avatar-img" src="../assets/sergio1.jpg" alt="">
                    <div class="avatar-text"><span><b>Sergio</b><br>Técnico Informático y Analista Programador recibido en la Universidad Nacional de Jujuy, actualmente estudio Danza en la Universidad Provincial de Córdoba. Me especializo en desarrollo web y marketing digital de forma autodidacta. Soy muy creativo y versátil </span></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Somos",
}
</script>

<style>
#somos{
    background: #f4f6ff;
}

.row-avatar{
    height:50%;
}

.avatar{
    margin: 10px 0 0 0;
}

.avatar-img{
    margin: 0 0 0 0;
    height: 40%;
    border-radius: 50%;
    box-shadow: 0 2px 10px 0 rgb(0 0 0 / 12%);
}

.avatar-text{
    padding: 15px 0 10px 0;
}
</style>    