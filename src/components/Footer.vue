<template>
    <div id="footer">
        <div class="container">
            <div class="row">
            <div class="col-sm">
                <h4 class="title-footer">----------</h4>
            </div>
                <div class="col-sm">
                    <h4 class="title-footer">Hablanos</h4>
                        <a class="btn btn-social mx-1" target="_blank" href="https://www.facebook.com/jallallaSD"><i class="fab fa-facebook-f"></i></a>
                        <a class="btn btn-social mx-1" target="_blank" href="mailto:jallallasd@gmail.com"><i class="far fa-envelope"></i></a>
                        <a class="btn btn-social mx-1" target="_blank" href="https://www.instagram.com/jallallasd/"><i class="fab fa-fw fa-instagram"></i></a>
                </div>
                <div class="col-sm">
                    <h4 class="title-footer">JALLALLA</h4>
                    <span>"porque estoy convencido de que serás lo que hay que ser, si no, eres nada"</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
#footer{
    padding: 30px 0 20px 0;
    background: #E50051;
}

.col-sm{
    padding-bottom: 30px;
}

.title-footer{
    margin-bottom: 1rem;
}

.fab{
    color: #000000;
}

.btn-social{
    border-radius: 100%;
    display: inline-flex;
    width: 3.25rem;
    height: 3.25rem;
    font-size: 1.25rem;
    color: #000000;
    border: 2px solid #000000;
    transition: all 200ms ease;
    justify-content: center;
    align-items: center;
}
.btn-social:hover{
    background: #F9B256;
    border: 2px solid #000000;
    color: #000000;
}

</style>