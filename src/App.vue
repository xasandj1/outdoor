<template>
  <div id="app">
    <Navbar />
    <main>
    <Home />
    <About />
    <Promise />
    <Family />
    <Navigeting/>
    <Suscribe/>
    </main>
    <Footer/>
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Promise from './components/Promise.vue'
import Family from './components/Family.vue';
import Navigeting from './components/Navigeting.vue';
import Suscribe from './components/Suscribe.vue';
import Footer from './components/Footer.vue';
export default {
  components: {
    Navbar,
    Home,
    About,
    Promise,
    Family,
    Navigeting,
    Suscribe,
    Footer
},
  data() {},
  methods: {},
};
</script>
<style>
@import './assets/base.css';

</style>
