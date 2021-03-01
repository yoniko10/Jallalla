<template>
  <Header />
  <Splash />
  <div class="about">
    <h1>jajaj acá seguimos trabajando vuelva pronto 🛠️</h1>
  </div>
  <Footer />
  <Copyright />

</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Splash from "@/components/Splash.vue";
import Footer from "@/components/Footer.vue";
import Copyright from "@/components/Copyright.vue";

export default {
  name: "Home",
  components: {
    Header,
    Splash,
    Footer,
    Copyright,
  }
};
</script>