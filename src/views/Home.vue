<template>
  <div class="home">
    <Header />
    <Splash />
    <Servicios />
    <Somos />
    <Footer />
    <Copyright />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Splash from "@/components/Splash.vue";
import Servicios from "@/components/Servicios.vue";
import Somos from "@/components/Somos.vue";
import Footer from "@/components/Footer.vue";
import Copyright from "@/components/Copyright.vue";

export default {
  name: "Home",
  components: {
    Header,
    Splash,
    Servicios,
    Somos,
    Footer,
    Copyright,
  }
};
</script>
