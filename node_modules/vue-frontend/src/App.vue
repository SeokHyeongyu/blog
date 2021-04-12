<template>
  <div id="app">
    <Header />
    <div id="page-top">
      <router-view></router-view>
      <Portfolio />
      <About />
      <Contact />
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from "./components/layout/Header.vue";
import Portfolio from "./components/layout/Portfolio.vue";
import About from "./components/layout/About.vue";
import Contact from "./components/layout/Contact.vue";
import Footer from "./components/layout/Footer.vue";
export default { 
  name: "App",
  components: {
    Header,
    Portfolio,
    About,
    Contact,
    Footer,
  },
};
</script>

<style>
</style>