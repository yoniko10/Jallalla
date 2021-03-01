<template>
<div id="header">
    <nav id="nav" class="navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"><img class="imagotipo" src="../assets/imagotipoHorizontalNegro.png" alt=""></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-Header" aria-controls="#navbar-Header" aria-expanded="false" aria-label="Toggle navigation" @click="collapseNavBar = !collapseNavBar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div :class="collapseNavBar ? 'collapse' : ''" class="navbar-collapse" id="navbar-Header">
                <ul class="navbar-nav">
                    <li class="nav-item mx-0 mx-lg-1">
                        <a class="nav-link active" href="#"><router-link to="/">HOME</router-link></a>
                    </li>
                    <li class="nav-item mx-0 mx-lg-1">
                        <a class="nav-link"><router-link to="/about">CONTACTO</router-link></a>
                    </li>
                    <li class="nav-item mx-0 mx-lg-1">
                        <a class="nav-link"><router-link to="/portfolio">PORTFOLIO</router-link></a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    
    
    <img id="llama" src="../assets/llama.gif" alt="">
</div>
    
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            collapseNavBar: true,
        }
    }
};
</script>

<style scoped>

#nav a{
    text-decoration: none;
    font-weight: bold;
    color: #000000;
    transition: all 150ms ease;
}

@keyframes mover {
    from {
        right: -50px;
    }
    to{
        right: 1500px;
    }
}

#llama{
    right: 10px;
    bottom: -10px;
    position: absolute;
    height: 50px;
    animation-name: mover;
    animation-iteration-count: infinite;
    animation-duration: 200s;
}

#nav a:hover{
    font-weight: bold;
    color: #F9B256;
}

#nav a.router-link-exact-active {
    background: #A30039;
    color: #000000;
}

#header{
    background: #E50051;
    top: 0;
    position: fixed;
    width: 100vw;
    padding: 1rem 1.5rem;
    align-content: center;
}

.nav-item{
    padding: 10px 20px 10px 20px;
    color: #F9B256;
}

.imagotipo{
    height: 60px;
}

h1 {
    margin: 0 0 0 0;
}
h4 {
    margin: 0 0 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
</style>